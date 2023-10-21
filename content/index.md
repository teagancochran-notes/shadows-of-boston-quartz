```dataview
TABLE WITHOUT ID file.link as Session, date as Date, title as Title, summary as Summary from "Sessions"
WHERE file.folder != file.name
SORT session asc
```
