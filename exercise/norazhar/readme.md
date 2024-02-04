# Hello World
## Hello World
### Hello World
#### Hello World

My name  **Norazhar Anas**, I'm *43 years old*
| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Row 1, Col 1 | Row 1, Col 2 | Row 1, Col 3 |
| Row 2, Col 1 | Row 2, Col 2 | Row 2, Col 3 |
| Row 3, Col 1 | Row 3, Col 2 | Row 3, Col 3 |

| Name            | IC Number    | Gender | Age | Address                           |
|-----------------|--------------|:--------:|-----:|-----------------------------------|
| Ahmad bin Ali   | 950201-14-5678| Male   | 30  | 123 Jalan Merdeka, Kuala Lumpur   |
| Siti binti Tan  | 881011-08-9876| Female | 25  | 456 Jalan Bunga Raya, Penang      |
| Hafizah bt Lim  | 900505-12-3456| Female | 32  | 789 Jalan Damai, Johor Bahru      |
| Amirul bin Raju | 970719-11-2345| Male   | 24  | 321 Jalan Sentosa, Kuching        |


## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```

And this will produce a flow chart:

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```

```mermaid
journey
    title My working day
    section Go to work
      Make tea: 5: Me
      Go upstairs: 3: Me
      Do work: 1: Me, Cat
    section Go home
      Go downstairs: 5: Me
      Sit down: 5: Me
```
