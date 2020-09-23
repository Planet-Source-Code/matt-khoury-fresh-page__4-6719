<div align="center">

## Fresh Page


</div>

### Description

To force the end user's browser to always load a new copy of your web page. Caution, this is a little more stressful on the server as it removes some of the client side rendering.
 
### More Info
 
Fresh current up-to-date web content.

A little more stressful on the server.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Matt Khoury](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/matt-khoury.md)
**Level**          |Intermediate
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |ASP \(Active Server Pages\), VbScript \(browser/client side\)

**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__4-9.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/matt-khoury-fresh-page__4-6719/archive/master.zip)





### Source Code

```
<%@ Language=VBScript %>
  <%
  	Option Explicit
  	Response.Expires = 0
  	Response.Buffer = True
  	Response.Clear
  %>
```

