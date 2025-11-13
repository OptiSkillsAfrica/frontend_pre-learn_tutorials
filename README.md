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

1. Type `!` and press **Tab**.  
   VS Code will automatically generate a basic HTML structure (called a _boilerplate_).

2. In the `<title>` section, replace **“Document”** with:

   ```
   HTML Fundamentals
   ```

## Step 4: Text content: headings, paragraphs, inline formatting

Inside <body>, add:

```
<header>
  <h1>HTML Fundamentals — Student Name</h1>
  <p class="lead">Learn by building a single page that includes common HTML elements.</p>
</header>

<main>
  <section id="text">
    <h2>Text and Formatting</h2>
    <p>This is a <strong>bold</strong> word, this is <em>italic</em>, and this is <mark>highlighted</mark>.</p>
    <p>Abbreviation example: <abbr title="HyperText Markup Language">HTML</abbr>.</p>
  </section>
</main>
```
