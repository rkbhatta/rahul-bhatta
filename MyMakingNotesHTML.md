Here's an example of what the folder structure might look like for an HTML-based academic profile website that uses a common layout template:

```
|-- index.html (homepage)
|-- css/
|   |-- styles.css
|-- teaching/
|   |-- index.html
|   |-- course1/
|   |   |-- notes.html
|   |   |-- assignments.html
|   |-- course2/
|   |   |-- notes.html
|   |   |-- assignments.html
|-- research/
|   |-- index.html
|   |-- project1/
|   |   |-- proposal.html
|   |   |-- report.html
|   |-- project2/
|   |   |-- proposal.html
|   |   |-- report.html
|-- cv/
|   |-- index.html
|-- templates/
|   |-- header.html
|   |-- sidebar.html
|   |-- footer.html
```

<!--You can use a template engine like Mustache, Handlebars or a server-side language like PHP, Ruby, Python, etc. to separate the layout and content of your pages.-->

The main files of the website will be the header.html, sidebar.html, and footer.html which will be included in the other pages.
Here's an example of what the index.html file might look like:

```
<!DOCTYPE html>
<html>
<head>
  <title>Academic Profile</title>
  <link rel="stylesheet" href="css/styles.css">
</head>
<body>
  <header>
    <include src="templates/header.html">
  </header>
  <div id="sidebar">
    <include src="templates/sidebar.html">
  </div>
  <div id="main-content">
    <h1>Welcome to my Academic Profile</h1>
    <p>This website contains my teaching notes, research profile, and CV.</p>
  </div>
  <footer>
    <include src="templates/footer.html">
  </footer>
</body>
</html>
```

To add shadows to the sidebar and the contact bar, you can use the CSS box-shadow property. Here's an example of what the CSS code for the sidebar and the contact bar might look like:

```
#sidebar {
  width: 200px;
  float: left;
  padding: 20px;
  box-shadow: 2px 2px 5px #ccc;
}

#footer {
  clear: both;
  text-align: center;
  padding: 10px;
  box-shadow: 2px 2px 5px #ccc;
}
```

here's an example of what the sidebar.html file might look like:

```
<img src="path/to/image.jpg" alt="Your Name">
<h3>Navigation</h3>
<ul>
  <li><a href="/teaching">Teaching</a></li>
  <li><a href="/research">Research</a></li>
  <li><a href="/cv">CV</a></li>
</ul>
```

And here's an example of what the footer.html file might look like:

```
<h3>Contact</h3>
<p>Email: your.name@example.com</p>
<p>Phone: 555-555-5555</p>
<p>Address: 123 Example St, City, State</p>
```

You can include these files in other pages using the include element or other template engine specific method.
