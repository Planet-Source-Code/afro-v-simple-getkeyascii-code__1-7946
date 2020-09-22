<div align="center">

## V\. Simple GetKeyAscii code


</div>

### Description

I have seen all of these really complex GetKeyAscii functions out there. Well check this out.
 
### More Info
 
You need to paste this code in the KeyUp section of the Form Code.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Afro](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/afro.md)
**Level**          |Beginner
**User Rating**    |4.3 (13 globes from 3 users)
**Compatibility**  |VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Files/ File Controls/ Input/ Output](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/files-file-controls-input-output__1-3.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/afro-v-simple-getkeyascii-code__1-7946/archive/master.zip)





### Source Code

```
Private Sub Form_KeyUp (KeyASCII as Integer, KeyCode as Integer)
Label1.Caption = KeyCode
End Sub
```

