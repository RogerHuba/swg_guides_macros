# Siymon's Macro File

- This is a copy of my macro file. 
- When I want to add new macros, I update this file, then replace text in macro file.
- This allows me to keep things in some type of order and makes it easier to find and edit on the fly.
- Many have asked why I have simple commands macroed. I do this so I can edit my hot keys. For example, I use my number pad to do certain things. The number pad 7 key is always the knockdown key, regardless of the toon I am on. On my Master Saber Jedi this is forcethrow, on my TMK this is unarmed knockdown, etc...You cannot assign hot keys to in commands so you need to creat a macro to do it.
- I personally sort mine by profession, but you can do how ever you want.
- You will notice a gap in numbers, this allows me to add more inbetween later on and not mess up my existing setup.

```text
version: 0000
AFKMAC spin #ffffff /pause 0.25;/tellpet s2;/ui action cycleareaself;/pause .5;/loot corpse all;/pause .5;/loot all;/pause .5;/stand;/ui action clearTarget;/ui action cycleTargetOutward;/taunt;/attack;/pause 3;/intimidate;/pause 2.5;/tellpet s1;/m AFKMAC;

TKM_SPIN_SAME spin #ffffff /pause 0.25;/unarmedspinattack2;/pause 1;/m TKM_SPIN_SAME;
TKM_SPIN_CYCLE spin #ffffff /pause 0.25;/cto;/pause .3;/unarmedspinattack2;/pause .8;/m TKM_SPIN_CYCLE;
TKM_COMBO spin #ffffff /pause 0.25;/intimidate;/unarmedblind1;/unarmedstun1;/unarmeddizzy1;/unarmedknockdown2;
TKM_MEDITATE spin #ffffff /pause 0.25;mediate;

SWORDS_SPIN_SAME spin #ffffff /pause 0.25;/melee2hspinattack2;/pause 2;/m SWORDS_SPIN_SAME
SWORDS_SPIN_CYCLE spin #ffffff /pause 0.25;/unarmedspinattack2;/pause 1;/m TKM-Spin;
SWORDS_COMBO spin #ffffff /pause 0.25;/intimidate1;/melee2harea3;/melee2hsweep2;

POLEARM_SPIN_SAME spin #ffffff /pause 0.25;/polearmspinattack2;/pause 1.5;/m POLEARM_SPIN_SAME;
POLEARM_SPIN_CYCLE spin #ffffff /pause 0.25;/cto;/påause .3;/unarmedspinattack2;/pause .8;/m TKM_SPIN_CYCLE;
POLEARM_COMBO spin #ffffff /pause 0.25;/intimidate;/unaårmedblind1;/unarmedstun1;/unarmeddizzy1;/unarmedknockdown2;
POLEARM_GRIND spin #ffffff /pause 0.25;/polearmspinattack2;/pause 1.5;/m POLEARM_GRIND;

FENCER_SPIN_SAME spin #ffffff /pause 0.25;/melee1hspinattack2;/pause 2;/m FENCER_SPIN_SAME;
FENCER_SPIN_CYCLE spin #ffffff /pause 0.25;/unarmedspinattack2;/pause 1;/m TKM-Spin;
FENCER_Combo spin #ffffff /pause 0.25;/intimidate1;/melee2harea3;/melee2hsweep2;

RANGED_SPIN_SAME spin #ffffff /pause 0.25;/pointBlankArea1;/pause 2;/m RANGED_SPIN_SAME;
RANGED_SPIN_CYCLE spin #ffffff /pause 0.25;/cto;/pointBlankArea1;/pause 2;/m RANGED_SPIN_CYCLE;
RIFLE_COMBO

GRIND_HEAL spin #ffffff /pause 0.25;/healDamage;/pause 15;/m grind_heal;

deathblow spin #ffffff /pause 0.25;/deathblow;/pause 1;/m deathblow;
COB spin #ffffff /pause 0.25;/center;/pause 31;/m COB;
forage spin #ffffff /pause 0.25;/forage;/pause 15;/m forage;
DUMP spin #ffffff /pause 0.25;/dump;/dump;
LOOT spin #ffffff /pause 0.25;/ui action cycleareaself;/pause .3;/loot corpse all;/pause .3;/loot all;/pause .5;/m LOOT;
PET_ATTACK spin #ffffff /pause 0.25;/tellpet s1;/pause 8;/tellpet s2;/pause 15;/m PET_ATTACK;
sample spin #ffffff /pause 0.25;/sample;/pause 30;/m sample;
oldman spin #ffffff /pause 0.25;/target an;/pause 3;/ui action radialMenu;/pause 3;/ui action defaultAction;/pause 3;/ui action conversationResponse0;/pause 3;/ui action conversationResponse0;/pause 3;/ui action conversationResponse0;/pause 3;/macro oldman;

foodChanad spin #ffffff /pause 0.25;/[tb00];/[tb01];/[tb02];/[tb03];/[tb04];/[tb05];/[tb06];/[tb07];/pause 1150;/m foodChanad;
foodProtien spin #ffffff /pause 0.25;/[tbP1];/[tb00];/[tb01];/[tb02];/[tb03];/[tbP0];/pause 20;/m foodProtien;
foodPikatta spin #ffffff /pause 0.25;/[tbP1];/[tb04];/[tb05];/[tb06];/[tb07];/[tbP0];/pause 1510;/m foodPikatta;

autoSaber spin #ffffff /pause 0.25;/saberPolearmDervish;/pause 6;/mac autoSaber;
forceHealHealthSelf spin #ffffff /pause 0.25;/ccq;/healHealthSelf1;
forceHealAllSelf spin #ffffff /pause 0.25;/ccq;/healAllSelf1;
forceHealActionSelf spin #ffffff /pause 0.25;/ccq;/healActionSelf;
forceIntimidateArea2 spin #ffffff /pause 0.25;/forceIntimidate2;
forceknockDown spin #ffffff /pause 0.25;/forceKnockdown3;

forcemeditate spin #ffffff /pause 0.25;/forceMeditate;
forceLightningSingle spin #ffffff /pause 0.25;/forceLightningSingle2;
forceLightningCone spin #ffffff /pause 0.25;/forceLightningCone2;

forceWeaken spin #ffffff /pause 0.25;/forceWeaken3;
forceMindBlast spin #ffffff /pause 0.25;/mindBlast2;
forceJediMindTrick spin #ffffff /pause 0.25;/jediMindTrick
forceThrow spin #ffffff /pause 0.25;/forceThrow2;
forceBreach spin #ffffff /pause 0.25;/forceBreach;
forceChoke spin #ffffff /pause 0.25;/forceChoke;
forceHealStates spin #ffffff /pause 0.25;/healStatesSelf;

forceHealMindSelf spin #ffffff /pause 0.25;/ui action clearCombatQueue;/healMindSelf1;

FORCE_FORTIFY_MAC spin #ffffff /pause 0.25;/fortify;/pause 29;/m FORCE_FORTIFY_MAC;
FORCERUN1 spin #ffffff /pause 0.25;/FORCERUN1;
FORCERUN2 spin #ffffff /pause 0.25;/FORCERUN2;
FORCERUN3 spin #ffffff /pause 0.25;/FORCERUN3;
FORCE_AVOID_INCAP spin #ffffff /pause 0.25;/avoidIncapacitation;/group RUNNING AVOID INCAP - FEED ME FORCE;/pause 29;/m FORCE_AVOID_INCAP;
ForceStopBleeding spin #ffffff /pause 0.25;/stopBleeding;
ForceCureDisease spin #ffffff /pause 0.25;/forceCureDisease;
ForceCurePosion spin #ffffff /pause 0.25;/forceCurePoison;

```
