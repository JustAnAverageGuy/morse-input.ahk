# morse-input.ahk
A simple AutoHotkey script which takes morse code input and converts it to corresponding characters

> [!NOTE]
> Written on AutoHotkey v1.1

Can use the following pairs as *dit-dah pairs*

| dit | dah |
| -------------- | --------------- |
| `.` | `-` |
| `>` | `_` |
| `[` | `]` |

If there is a single match for the given sequence, it will be replaced, otherwise you can trigger the expansion manually by inputting a character among `EndChars` i.e. 
```
(){}:;'"/\,?!`n `t
```

(I wrote this script long time ago, I don't remember what is '\`n' and '\`t')

> [!NOTE]
> If you want this to work in VSCode, just remove the `#IfWinNotActive` clause from the script

