# PVP Macros

## Introduction

Built on the shoulders of wookies.

All the macros that start with `clearCombatQueue` will dump all pending attacks in your combat queue, effectively interrupting whatever you were doing previously. This is mostly applied to heals and state debuffing, it's worth noting that by specifying `self` we don't need to change target, which would otherwise futz with our pvp. 

These macro's assume you have the standard Doctor `4x3x` as part of your template, otherwise some of these will not be available to you, and the bleed is from Fencer. 

## Doctor

### pvpCureDisease

```swg
/ui action clearCombatQueue;
/curedisease self;
```

### pvpCurePoison

```swg
/ui action clearCombatQueue;
/curepoison self;
```

### pvpExtinguishFire

```swg
/ui action clearCombatQueue;
/extinguishFire self;
```

### pvpFirstAid

```swg
/ui action clearCombatQueue;
/firstAid self;
```

### pvpHealDamage

```swg
/ui action clearCombatQueue;
/healdamage self;
```

### pvpHealState

```swg
/ui action clearCombatQueue;
/healState self;
```

## Combat

### pvpDeathblow

```swg
/deathblow;
/pause 1;
/macro pvpDeathblow;
```

### pvpIntimidate

```swg
/ui action clearCombatQueue;
/intimidate;
```

### pvpWarcry

```swg
/ui action clearCombatQueue;
/warcry1;
/peace;
```

### pvpCOB

```swg
/center;
/pause 31;
/macro pvpCOB;
```

### pvpBleed

```swg
/melee1hhealthhit2;
/melee1hhealthhit1;
```

## Force Healing

### Heal Health Self

```
/ui action clearCombatQueue;
/healHealthSelf;
```

### Heal Action Self

```swg
/ui action clearCombatQueue;
/healActionSelf;
```

### Heal Mind Self

```swg
/ui action clearCombatQueue;
/healMindSelf;
```

### Heal All Self

```swg
/ui action clearCombatQueue;
/healAllSelf;
```

### Total Heal Self

```swg
/ui action clearCombatQueue;
/totalHealSelf;
```

### Stop Bleeding

```swg
/ui action clearCombatQueue;
/stopBleeding self;
```

### Force Cure Disease

```swg
/ui action clearCombatQueue;
/forceCureDisease self;
```

### Force Cure Poison

```swg
/ui action clearCombatQueue;
/forceCurePoison self;
```

### Heal States Self

```swg
/ui action clearCombatQueue;
/healStatesSelf;
```

### Purge

```swg
/ui action clearCombatQueue;
/healStatesSelf;
/forceCurePoison self;
/forceCureDisease self;
/stopBleeding self;
```

#### References

TODO: Add a reference
