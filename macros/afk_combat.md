# Macro for AFK Combat

## Description
This macro will find a target every 15 seconds and throw an intimidate at it. It is not intended for at keyboard combat automation. It's intended use is afk farming static spawns outside of majour NPC cities. No buffs required, but reasonable armour minisuit probably mandatory. 

### Macro: `afkstatic`
```
/stand;
/ui action untarget;
/ui action cycleTargetOutward;
/pause 1;
/intimidate;
/pause 1;
/attack;
/pause 12;
/m afkstatic;
```

### Macro: `fightafk`

This macro will find the closest target every 2 seconds. 

Because the macro always targets you first at the start of the loop, the cycleTargetOutward will always land on the nearest enemy. 

```
/stand;
/ui action untarget;
/ui action cycleTargetOutward;
/attack;
/pause 2;
/macro fightafk;
```

I should try `/ui action untarget` in place of `/ui action targetSelf` as apparently this will not drop the current target if it's still alive!

