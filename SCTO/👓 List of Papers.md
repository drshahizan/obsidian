
> [!NOTE] Explanation
> This is some Obsidian wizardry using the [plugin dataview.](https://github.com/blacksmithgu/obsidian-dataview) It requires some expertise to fully customize. But the idea is that you can qrite custom queries to your notes and filter only those that have specific meta data or tags in them. Here are a few examples. (If it does not work, go to settings, activate community plugins and add "dataview")

# All Papers
All papers in primary sources folder, sorted by rating

```dataview
TABLE without id file.link as Paper, ShortSummary as Summary, Rating FROM "1️⃣ Primary Sources" sort Rating DESC
```

# Review Papers
Papers with a #reviewpaper tag.

```dataview
TABLE without id file.link as Paper, ShortSummary as Summary, Rating FROM #reviewpaper AND "1️⃣ Primary Sources"  sort Rating DESC
```


# Machine Learning Papers
Papers with a #Machine_learning   tag.

```dataview
TABLE without id file.link as Paper, ShortSummary as Summary, Rating FROM #Machine_learning  AND "1️⃣ Primary Sources"  sort Rating DESC
```



> [!fail]- Papers in need of a tag!
> Please provide a tag for these papers: 
> ```dataview
> table without id file.link as Paper, Summary, Rating from "1️⃣ Primary Sources" where length(file.tags) = 0
> ```
