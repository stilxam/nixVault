```dataview
TABLE
file.ctime as Created
FROM #todo
SORT file.ctime DESC
LIMIT 10
```
