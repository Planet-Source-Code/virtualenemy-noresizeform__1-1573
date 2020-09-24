<div align="center">

## noresizeform


</div>

### Description

DUHH
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Virtualenemy](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/virtualenemy.md)
**Level**          |Unknown
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[String Manipulation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/string-manipulation__1-5.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/virtualenemy-noresizeform__1-1573/archive/master.zip)





### Source Code

```
Public Sub NoResizeForm()
Dim hMenu As Long
    Const SC_SIZE = &HF000
    Const MF_BYCOMMAND = &H0
    hMenu = GetSystemMenu(hwnd, 0)
    Call DeleteMenu(hMenu, SC_SIZE, MF_BYCOMMAND)
End Sub
```

