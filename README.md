# Headline Board

Welcome to the **Headline Board** project! This simple yet stylish webpage displays a headline with an image and some text in a visually appealing manner. Below you'll find a brief overview of how the project is structured and how to get started.

## Project Structure

This project consists of an HTML file and a CSS file:

1. **`index.html`** - Contains the HTML structure of the page.
2. **`styles.css`** - Contains the CSS styles for the page.

### HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Headline Board</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="headline-board">
      <img
        src="Images/images.png"
        alt="Headline Image"
        class="headline-image"
      />

      <div class="headline-text">
        <h1 class="headline-title">
          Tokoloshe
          <br />
          Robs
          <br />
          Spaza
        </h1>
      </div>
    </div>
  </body>
</html>
