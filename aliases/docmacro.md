# Alias Name: Aliases for Buff By Keyword

## Author
Siymon

### Description
- Here are multiple aliases needed for the buff by keyword macro.

#### Alias Text

- This alias triggers the /broadcase macro (boradcase macro must be set in macros.txt)
```text
[broadcast] /m broadcast
```

- This alias will backspace the curser to get it at the right position. This must be modified specifically for your character based the name of the channel you create.
```text
[bs20] /ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;
```

- This alias will clear your tell queue and also clear the chatlog text file.
```text
[clear] /tell jeddah ----------MESSAGES-CLEARED----------;
```

This alias will be used to create the macro for the buff commands. When the chat sees the `[cmd]` text it will replace it with the `/m` which will start the execution of a macro. 
```text
[cmd] /m
```

- These aliases are used for grabing information from a tell and from the chatlog.txt file.
```text
[decrypter-off] /unalias [decrypter];
[decrypter-on] /alias [decrypter] /m decrypter;
[decrypter] /m decrypter;
[scanner] /m scanner
```

- This alias will move to ToolBarPane 1 (they are labled 0-5 to this will go to the second one), and then execute every ToolBarSlot 0 through 23 on that ToolBarPane and then go back to ToolBarPane 0. This is normally where I put bivoli, brandy, or havala if that is used. I typically did not use havala as it would fill up my stomach to quickly during large buff sessions and when that happens can cause the buffbot macro to fail.
```text
[use-food] /[TBP1];/[TB00];/[TB01];/[TB02];/[TB03];/[TB04];/[TB05];/[TB06];/[TB07];/[TB08];/[TB09];/[TB10];/[TB11];/[TB12];/[TB13];/[TB14];/[TB15];/[TB16];/[TB17];/[TB18];/[TB19];/[TB20];/[TB21];/[TB22];/[TB23];/[TBP0];
```

- This alias is used for backspacing to a specific area to create the macro.
```text
[vbs] /ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;/ui action chatBackspace;
```

- This alias is used to target a specific player in the macro.
```text
ll /tar
```
