Folder structure for My website files

```
|-- index.md (homepage)
|-- css/
|   |-- styles.css
|-- coursenotes/
|   |-- index.md (teaching notes index page)
|   |-- course1/
|   |   |-- notes.md
|   |   |-- assignments.md
|   |-- course2/
|   |   |-- notes.md
|   |   |-- assignments.md
|-- research/
|   |-- index.md (research index page)
|   |-- project1/
|   |   |-- proposal.md
|   |   |-- report.md
|   |-- project2/
|   |   |-- proposal.md
|   |   |-- report.md
|-- cv/
|   |-- index.md (cv page)
```

Template for the `index` pages

```
---
layout: default
---

# Welcome to my Academic Profile

This website contains my teaching notes, research profile, and CV.

## Navigation
- [Teaching](/teaching)
- [Research](/research)
- [CV](/cv)
```

Content for the `styles.css` file

```
/* Add your own custom styles here */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

#sidebar {
    width: 200px;
    float: left;
    padding: 20px;
}

#main-content {
    margin-left: 220px;
    padding: 20px;
}

#footer {
    clear: both;
    text-align: center;
    padding: 10px;
}
```
