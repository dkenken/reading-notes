# What is CSS?

CSS (Cascading Style Sheets) allows you to create great-looking web pages, but how does it work under the hood? This article explains what CSS is, with a simple syntax example, and also covers some key terms about the language.

## HTML

<!doctype html>
<html lang="en"> 
<head>
    <meta charset="utf-8">
    <title>Getting started with CSS</title>
</head>

<body>

    <h1>I am a level one heading</h1>

    <p>This is a paragraph of text. In the text is a <span>span element</span>

    <p>This is the second paragraph. It contains an <em>emphasized</em> element.</p>

    <ul>
        <li>Item <span>one</span></li>
        <li>Item two</li>
        <li>Item <em>three</em></li>
    </ul>

</body>

</html>

## CSS
h1 {
color: red;
font-size: 5em;
p, li {
color: green;
}
