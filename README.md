# Bigram Lab

A small interactive website that teaches the basic idea behind a bigram model. Visitors can enter text, inspect every neighboring word pair, see the next-word table, and ask the model to predict what follows a word.

The bigram counting and prediction logic is written in Python. The page runs that Python in the browser using Pyodide; JavaScript only connects the page controls to the Python code and displays the results.

## Run it locally

Run `python3 -m http.server` in this folder and visit `http://localhost:8000`. Pyodide is loaded from its CDN, so the first load may take a few seconds.

## Publish with GitHub Pages

1. Create a GitHub repository and add the files in this folder.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**, choose your main branch and `/ (root)`, then save.
4. GitHub Pages will provide a public URL after it finishes deploying.

The site uses the Pyodide CDN and Google Fonts, so visitors need an internet connection.
