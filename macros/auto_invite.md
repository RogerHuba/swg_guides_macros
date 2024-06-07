# Macro to Auto Invite Macro

## Description
This macro will invite someone when they send you a tell. Can invite anyone on any planet.

### Alias

Write this into your chat bar and run once to create the entry in the `alias.txt` file.

```
/alias ll /invite
```

### Macro: `invite`
Replace `[your name]` with your characters first name, delete the brackets.

```text
/ui action startChatReply;
/ui action chatCursorHome;
/ui action chatCursorRight;
/ui action chatDelete;
/ui action chatDelete;
/ui action chatEnter;
/tell [your name] Auto Invite is running....;
/pause 8;
/m invite;
```



Now all anyone has to do is send you a tell and you will auto target them and send them a group invite. You must be the group leader in order to do this.
The `/tell` in the 3rd to last line sends yourself a message so you don't end up spamming the last person you sent an invite to.

## References

* [Auto Invite Macro](https://swgprophecy.com/showthread.php?tid=727)
* [Floman's Invite By Tell Macro - With Chat Logging](https://www.swgemu.com/forums/showthread.php?t=247605)
