# Case study 1

In Dataview, the `LIST` command is used to display a list of items based on the filtering or querying criteria specified. It allows you to present a simplified view of your data without the need for a table format.

For example, a Query can look like this:

### Sample 1
````plain
```dataview 
LIST file.ctime
```
````

```dataview 
LIST file.ctime
```

### Sample 2
````plain
```dataview 
LIST FROM "1️⃣ Primary Sources" where rating > "3/5"
```
````

```dataview 
LIST FROM "1️⃣ Primary Sources" where rating > "3/5"
```

### Sample 3
````plain
```dataview
LIST
FROM "📆 Activity"
```
````

```dataview
LIST
FROM "📆 Activity"
```

### Sample 4
````plain
```dataview
LIST
WHERE file.mtime >= date(today) - dur(1 week)
```
````

```dataview
LIST
WHERE file.mtime >= date(today) - dur(1 week)
```

### Sample 5: List Workout Logs
````plain
```dataview
TABLE workout
FROM "2️⃣ Collections"
SORT file.ctime DESC
LIMIT 14
```
````

```dataview
TABLE workout
FROM "2️⃣ Collections"
SORT file.ctime DESC
LIMIT 14
```

# Case study 2
The code you provided appears to be written in Dataview, a tool for organizing and manipulating data in a document format. Dataview is often used as a plugin for the note-taking application Obsidian.

Let's break down the code:
````plain
```dataview 
TABLE DOI, Title FROM "1️⃣ Primary Sources" where rating = "5/5"
```
````
- `TABLE`: This keyword is used to specify that you want to display a table of data.

- `DOI, Title`: These are the fields or columns you want to include in the table. In this case, you want to include the "DOI" and "Title" fields.

- `FROM "1️⃣ Primary Sources"`: This specifies the source or document from which the data should be retrieved. In this case, the source is named "1️⃣ Primary Sources."

- `where rating = "5/5"`: This is a filter condition that selects only the rows where the "rating" field is equal to "5/5."

Putting it all together, the code is instructing Dataview to create a table that includes the "DOI" and "Title" fields from the document named "1️⃣ Primary Sources," but only for entries where the "rating" is "5/5". The result will be a table displaying the DOI and Title information for items with a rating of 5/5 from the specified source.

### Results:
```dataview 
TABLE DOI, Title FROM "1️⃣ Primary Sources" where rating = "5/5"
```

# Case study 3

### List Completed Tasks
````plain
```dataview
TASK
WHERE !completed
LIMIT 10
GROUP BY file.link
SORT rows.file.ctime ASC
```
````

```dataview
TASK
WHERE !completed
LIMIT 10
GROUP BY file.link
SORT rows.file.ctime ASC
```

# Case study 4: Calendar
````plain
```dataview
CALENDAR file.mtime
FROM ""
```
````

```dataview
CALENDAR file.mtime
FROM ""
```

# Case study 4: Task
````plain
```dataview
TASK
```
````

```dataview
TASK
```