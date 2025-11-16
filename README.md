# HTML Tutorials

## Step 1: Create Your Project Folder

1. On your desktop or any folder of your choice, **right-click** and select **New Folder**.
2. Name the folder **`myfirsthtmlpage`**.

This will be our main project directory where all files for this tutorial will live.

---

## Step 2: Open the Folder in VS Code

1. Open **Visual Studio Code (VS Code)**.
2. Go to the **Explorer Panel** (usually on the left sidebar).
3. Click **“Open Folder”** and select the `myfirsthtmlpage` folder you just created.

You should now see an empty folder in your VS Code workspace.

---

## Step 3: Create an HTML File

1. Inside VS Code, create a new file and name it **`index.html`**.

   > `index.html` typically represents the homepage of a website.

---

## Step 4: Generate the HTML Boilerplate

Inside your `index.html` file:

Type `!` and press **Tab**.  
VS Code will automatically generate a basic HTML structure (called a _boilerplate_).

### Explanation:

- `<!DOCTYPE html>` declares this as an HTML5 document
- `<html>` is the root element with language attribute
- `<head>` contains meta information
- `<body>` contains the visible page content

## Step 5: Understanding the Head Section

Replace the code between `<head>` and `<\head>` with:

```
<meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <meta name="description" content="A personal portfolio showcasing HTML skills">
 <meta name="keywords" content="HTML, portfolio, web development">
 <meta name="author" content="Your Name">
 <title>My Portfolio - HTML Basics</title>
 <link rel="stylesheet" href="styles.css">
 <style>
     /* Internal CSS will go here later */
     body { font-family: Arial, sans-serif; }
 </style>
```

### Key Points:

- Meta tags provide information to browsers and search engines
- The title appears in browser tabs
- You can link external CSS or write internal styles

## Step 6: Text elements: headings, paragraphs, inline formatting

Inside <body>, add:

```
<h1>Welcome to My HTML Portfolio</h1>
<h2>About Me</h2>
<h3>My Skills</h3>
<h4>HTML Level: Beginner</h4>

<p>This is a paragraph about my journey learning HTML. I can create <strong>bold text</strong>,
<em>italic text</em>, and <u>underlined text</u>.</p>

<p>I'm learning to create<br>line breaks<br>within paragraphs.</p>

<blockquote>
    "The best way to learn is by doing." - This tutorial
</blockquote>

<pre>
This is preformatted text.
It preserves both spaces
and line breaks exactly
as they appear in code.
</pre>

<p>I can write <code>inline code</code> within paragraphs.</p>
```

## Step 7: HTML Entities

Just below the last `<p>` block, add:

```
<h2>HTML Entities Practice</h2>
<p>Less than: &lt; &#60;</p>
<p>Greater than: &gt; &#62;</p>
<p>Ampersand: &amp; &#38;</p>
<p>Copyright: &copy; &#169;</p>
<p>Registered trademark: &reg; &#174;</p>
<p>Non-breaking space: Hello&nbsp;World&nbsp;&nbsp;&nbsp;Extra&nbsp;Spaces</p>
<p>Quotation marks: &quot;Hello World&quot; &#34;</p>
<p>Euro: &euro; &#8364;</p>
```

## Step 8: Creating Hyperlinks

## Step 10: Working with Images

## Step 11: Working with Videos and Audios

## Step 12: Lists

## Step 13: Tables

## Step 14 Containers

## Step 15 Semantic Elements
