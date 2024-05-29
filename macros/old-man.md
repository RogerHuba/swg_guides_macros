# Script
old_man

## Description
Tired of waiting around for the old man to show up. Run this script afk and if he visits, you will talk and accept the quest. You might get jumped by 2 sith if you are AFK, but if you are a combat profession should not be a problem.

### Macro: old_man
``` text
/target an;
/pause 3;
/ui action radialMenu;
/pause 3;
/ui action defaultAction;
/pause 3;
/ui action conversationResponse0;
/pause 3;
/ui action conversationResponse0;
/pause 3;
/ui action conversationResponse0;
/pause 3;
/macro old_man;
```