# Cost Formulae
As of TokenEnchant v15, you can also define various different costing formulae to calculate how much does it cost to enchant a certain enchantment at a certain level.

You can specify any costing function defined in the CostFormulae.js and specify it in each Custom Enchantment's ```cost_formula:``` option.  Or you can define the default cost formula in TokenEnchant's config.yml using ```DefaultFormula:``` option.  The default ```DefaultFormula:``` value is ```linear_diff```.

## default CostFormulae.js
```
//CostFormulae.js
/*
base: base price set in price: option,
current: current level,
next: target level,
*/

function constant(base, current, next) {
    return base;
}

function constant_diff(base, current, next) {
    return base * (next - current);
}

function linear_diff(base, current, next) {
    var ret = 0;
    current++;
    next++;
    for (var i = current; i < next; i++) {
        ret += (i * base);
    }
    return ret;
}

function exponential1(base, current, next) {
    var ret = 0;
    for (var i = current; i < next; i++) {
        ret += base * Math.pow(i, 1.8);
    }
    return ret;
}

function power2(base, current, next) {
    var ret = 0;
    for (var i = current; i < next; i++) {
        ret += base * Math.pow(2, i);
    }
    return ret;
}

function step(base, current, next) {
    var unit_cost;
    if (next < 5)        // level 0 - 4
        unit_cost = 10;
    else if (next < 10)  // level 5 - 9
        unit_cost = 20;
    else                 // level 10 and above
        unit_cost = 50;
    return (next - current) * unit_cost;
}
```

## Examples

* If We wish to have a step function (each level up costs 10 between level 0 - 4, and costs 20 between level 5 - 9, and costs 50 at level 10 and above) for the ```Excavation``` enchantment, we can do something like below.  The option value ```step``` is the name of the function (```function step(base, current, next)```) in the ```CostFormulae.js```.  With this option, even when the default costing function is ```linear_diff```, ```step``` function will be used to calculate the cost for leveling up the ```Excavation``` custom enchantment.
```
Potions:
  Excavation:
    description: "It is just like Explosive but it will remove entire cuboid!"
    event_map:
      BlockBreakEvent: "HIGHEST"
      TEBlockExplodeEvent: "MONITOR"
    price: 10
    max: 10
    cost_formula: step
...
```

