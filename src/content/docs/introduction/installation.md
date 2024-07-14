---
title: Installation & quick start
---

Get ready to explore the innovative approach of radial design with Orbit! This guide will help you quickly get started and install everything you need.

### Step 1: Include Orbit stylesheet

To start using Orbit, include its CSS in your HTML file. You have two options:

1. **Download or Import the CSS file**:
   - **Download**: Download the CSS file from [Orbit's repository](#) and link it in your HTML file:
     ```html
     <head>
       <link rel="stylesheet" href="path/to/orbit.css">
     </head>
     ```
   - **Import**: Add the following to your stylesheet:
     ```css
     @import url('path/to/orbit.css');
     ```

2. **Include via CDN**:
   - Add this to your HTML file:
     ```html
     <head>
       <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@zumerlab/orbit/orbit.css">
     </head>
     ```

### Step 2: Include Orbit JavaScript (Recommended)

If you plan to use additional features like radial progress bars, curved text, and sectors, include Orbit's JavaScript. You can do this in two ways:

1. **Download the JavaScript file**:
   - Download from [Orbit's repository](#).
   - Link it in your HTML file:
     ```html
     <head>
       <script src="path/to/orbit.js" defer></script>
     </head>
     ```

2. **Include via CDN**:
   - Add this to your HTML file:
     ```html
     <head>
       <script src="https://cdn.jsdelivr.net/npm/@zumerlab/orbit/orbit.js" defer></script>
     </head>
     ```

### Step 3: Set up Orbit layout

Now, create a container with the `orbit-zone` class, and within it, add a radial layout using the `orbit` class. Inside the `orbit`, add elements with the `satellite` class. Here’s a minimal working example:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="/path/to/orbit.css" />
    <script src="/path/to/orbit.js" defer></script> <!-- Only if using additional features -->
    <title>Orbit Quick Start</title>
  </head>
  <body>
    <div class="orbit-zone">
      <div class="orbit">
        <div class="satellite">1</div>
        <div class="satellite">2</div>
        <div class="satellite">3</div>
      </div>
      <div class="orbit">
        <o-label>Curved text</o-label>
      </div>
    </div>
  </body>
</html>
```

### Step 4: Install via Package Manager (Optional)

You can also install Orbit using npm or yarn for easier management in your project:

```sh
npm install @zumerlab/orbit
```

## Next steps

Congratulations! You have successfully integrated Orbit into your project. Now, you can explore more advanced features and customization options. Check out the full documentation for detailed guides and examples. 

Happy coding!

