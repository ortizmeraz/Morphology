```dataview
TABLE Author,Title ,Year,status as "Status", fullref as "Full Citation"  
FROM #Article
FLATTEN File 
SORT status ASC
```