# Under Construction Landing Page Template

This project contains a polished "Under Construction" landing page template that can be used in any web project.

Use it for:

- temporary maintenance pages
- coming soon screens
- placeholder pages during development
- embedding into a larger site as a standalone component

## How to use

1. Copy `index.html` into your project.
2. Update the text, styles, and assets to match your brand.
3. Use it as a standalone page or embed it in another HTML page.

## Embed as an iframe

You can embed the full page in another HTML document using an iframe like this:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Under Construction Page</title>
    <style>
        /* Remove default margins and hide scrollbars on the main page */
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            overflow: hidden; 
        }

        /* Force the iframe to fill the entire viewport */
        iframe {
            width: 100vw;
            height: 100vh;
            border: none;
            display: block; /* Removes the tiny default bottom gap */
        }
    </style>
</head>
<body>

    <iframe 
        src="https://thefallenmaster.github.io/OnDevelopment/" 
        title="Under Construction Page">
    </iframe>

</body>
</html>
```

If your page is hosted in a different folder, update the `src` path accordingly.

## Notes

- The template includes a colorful animated background and a bubble-popping interaction.
- It is intentionally lightweight and easy to customize.
- You can replace the message and styles while keeping the page layout and animation logic.
