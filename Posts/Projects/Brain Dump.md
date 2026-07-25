---
date: 2026-07-24
---

# Brain Dump (This Website)

I made this up initially with intent to use only:
- HTML
- CSS
- JS

And in a way that is all I use but I make use of libraries now cause why waste time writing something obsolete. Libraries are there for a reason so use them.

The project makes use of vite to build the website, cause it provides a code structure I can work behind.

The source code of the website is generated through vite and hosted through github pages and redirectly through cloudflare to give the URL.

Current structure looks like this (After vite generates build):
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

The project makes use of:
- Marked (To convert markdowns into HTML)
- Highlight.js (For syntax highlighting in codeblocks)
- MathJax (For rendering math symbols)

Future:
- Grey Matter (For YAML Parsing, used in metaData)
- Some library for searching through posts