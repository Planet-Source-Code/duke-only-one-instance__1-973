<div align="center">

## Only one Instance


</div>

### Description

If the programm runs, you can't start it again!
 
### More Info
 
base module(insert the code)

change in project/options "form1" into "Sub Main"


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[DUKE](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/duke.md)
**Level**          |Unknown
**User Rating**    |4.0 (4 globes from 1 user)
**Compatibility**  |VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Complete Applications](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/complete-applications__1-27.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/duke-only-one-instance__1-973/archive/master.zip)





### Source Code

```
Sub Main()
Dim OldTitle$
  If App.PrevInstance Then
    OldTitle = App.Title
    App.Title = "Newapp.exe"
    AppActivate OldTitle
    End
  End If
  Form1.Show
End Sub
```

