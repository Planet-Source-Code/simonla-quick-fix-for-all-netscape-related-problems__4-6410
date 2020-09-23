<div align="center">

## Quick fix for all Netscape related problems


</div>

### Description

This code fixes *ALL* Netscape problems.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[SimonLa](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/simonla.md)
**Level**          |Intermediate
**User Rating**    |3.4 (61 globes from 18 users)
**Compatibility**  |ASP \(Active Server Pages\)
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__4-9.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/simonla-quick-fix-for-all-netscape-related-problems__4-6410/archive/master.zip)





### Source Code

```
<%
If InStr(request.servervariables("HTTP_USER_AGENT"), "MSIE") = 0 then
	Response.Write ("<br><br><br><br><table border=1 align=center bordercolorlight='#990000' bordercolordark='#990000' cellspacing=0 cellpadding=30><tr><td align=center><font face='Verdana,Arial,Helvetica' size='2'><font color='#990000'>We're sorry, this web site does not support primitive browsers.</font><p>Get a <a href='http://www.microsoft.com/ie/'><b>real one</b></a> !</font></td></tr></table>")
	Response.End
End If
%>
```

