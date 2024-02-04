Hi! I'm your first *Markdown* file in **StackEdit**. If you want to learn about StackEdit, you can ~~read me~~. If you want to play with Markdown, you can edit me. **Once** you have finished with me, you can ~~create new~~ files by opening the **file explorer** on the left corner of the navigation bar.
There are two types of synchronization and they can complement each other:

- The workspace synchronization will sync all your files, folders and settings automatically. This will allow you to fetch your workspace on any other device.
	> To start syncing your workspace, just sign in with Google in the menu.

- The file synchronization will keep one file of the workspace synced with one or multiple files in **Google Drive**, **Dropbox** or **GitHub**.
	> Before starting to sync files, you must link an account in the **Synchronize** sub-menu.

# Publication

Publishing in StackEdit makes it simple for you to publish online your files. Once you're happy with a file, you can publish it to different hosting platforms like **Blogger**, **Dropbox**, **Gist**, **GitHub**, **Google Drive**, **WordPress** and **Zendesk**. With [Handlebars templates](http://handlebarsjs.com/), you have full control over what you export.

[(Full Album) ITZY (있지) PLAYLIST ALL SONGS 2024](https://youtu.be/jPGNcN1GHFE?si=U1QbhJxPWtOgtAUD)

## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).

## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

```mermaid
sequenceDiagram
Yitkhee17 ->> wj: Hello Wj, how are you?
wj -->>Veron: How about you Veron?
wj -x Yitkhee17 : I am good thanks!
wj -x Veron: I am good thanks!
Note right of Veron: Wj thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

wj -->Yitkhee17 : Checking with Veron...
Yitkhee17 ->Veron: Yes... Veron, how are you?
