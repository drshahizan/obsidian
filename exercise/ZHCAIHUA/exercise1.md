For lecturers and academics, GitHub Education offers a range of resources to help them teach technology skills, including Lesson Plans, Classroom Tools, and Professional Development resources. These resources are designed to help teachers create and deliver effective technology courses and programs, and to help students develop the skills they need to succeed in the technology industry.


[a film link](https://www.youtube.com/live/86ZkbwYi1PI?feature=shared)
## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

```mermaid
sequenceDiagram
ZHU CAIHUA ->> Bob: Hello Bob, how are you?
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
