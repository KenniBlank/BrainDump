# Brain Dump (This Website)

I made this up initially with intent to use only: `HTML CSS JS`

And in a way that is all I use but I make use of libraries(for markdown parsing, code highlighting, and math rendering) now cause why waste time writing something obsolete.
> Libraries are there for a reason so use them!

The source code of the website is generated through vite and hosted through github pages and redirectly through cloudflare to give the URL.

(The underlying Vite project used to build this website is currently private because it is unstable and heavily opinionated. The generated output, however, is public and hosted on [GitHub](https://github.com/KenniBlank/BrainDump).)

Current structure looks like this (vite generated build):
```md
./
├── assets/
│   ├── script.js
│   └── style.css
├── Posts/
│   ├── images/
│   │   └── placeholder.jpg
│   └── Placeholder.md
├── favicon.svg
├── index.html
└── tree.md
```

The file `tree.md` is a special one, it is the navigation page that lists all the posts.
```md
---
Structure example of tree.md
---

- Projects
	- [Brain Dump](<Posts/Projects/Brain Dump.md>)
- [Placeholder](<Posts/Placeholder.md>)
- [RAG-101](<Posts/RAG-101.md>)
```
Here, `<>` is used for file links as it allows special characters in file name like space.

Currently, the project makes use of:
- [Marked](https://marked.js.org/) (To convert markdowns into HTML)
- [Highlight.js](https://highlightjs.org/) (For syntax highlighting in codeblocks)
- [MathJax](https://www.mathjax.org/) (For rendering math symbols)

<!--Future:
- [ ] Grey Matter (For YAML Parsing, used in metaData)
- [ ] Some library for searching through posts-->