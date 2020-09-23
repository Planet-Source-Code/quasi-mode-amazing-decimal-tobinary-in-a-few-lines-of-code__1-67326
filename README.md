<div align="center">

## AMAZING DECIMAL TOBINARY IN A FEW LINES OF CODE


</div>

### Description

make a DEC2BIN code easy and quick to run.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[QUASI\-MODE](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/quasi-mode.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0, VB Script, ASP \(Active Server Pages\) , VBA MS Access, VBA MS Excel
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/quasi-mode-amazing-decimal-tobinary-in-a-few-lines-of-code__1-67326/archive/master.zip)





### Source Code

```
Asume that you have a dialog form with a commandbutton, a textbox and a label on it.
Private Sub Command1_Click()
Dim I
Label1.Caption = ""
For I = 7 To 0 Step -1
  Label1.Caption = Label1.Caption + Str((Text1.Text And 2 ^ I) / 2 ^ I)
Next I
End Sub
put a number in the textbox, click on the command and the label will show the binary secuence.
it's works. I promise!
it use bit mask to get to the bits on the bytes.
```

