<div align="center">

## Self Refreshing Page


</div>

### Description

You can cause a page to automatically refresh every n seconds using the HTML Meta Refresh. This is great for chat sites, real time monitoring sites or any other site where you must have up to date real-time information.

This example will reload itself every 5 seconds and display the current time. Note: Replace the name test3.asp with whatever name you call this script.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Ian Ippolito \(vWorker\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/ian-ippolito-vworker.md)
**Level**          |Intermediate
**User Rating**    |4.6 (23 globes from 5 users)
**Compatibility**  |ASP \(Active Server Pages\)
**Category**       |[Server Side](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/server-side__4-31.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/ian-ippolito-vworker-self-refreshing-page__4-43/archive/master.zip)





### Source Code

```
<%@ LANGUAGE="VBSCRIPT" %>
<%option explicit
Response.Write "<META HTTP-EQUIV=REFRESH CONTENT=""5; URL=test3.asp"">"
%>
This page will refresh in 5 seconds...
<%= Now%>
```

