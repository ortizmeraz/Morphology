```dataview
TABLE Author,Title ,Year,status as "Status", fullref as "Full Citation"  
FROM #Concept 
FLATTEN File 
SORT status ASC
```



{/sum_{j}_}