---
title: Installation & quick start
---

Get ready to explore the innovative approach of radial design with Orbit! This guide will help you quickly get started and install everything you need.

### Step 0: Try Orbit online

To quickly get a taste of Orbit, you can try it directly in a <a href="https://codepen.io/pen?template=KKjaoRj" target="_blank">Ortbi Codepen Template</a>.



### Step 1: Include Orbit stylesheet

To start using Orbit, include its CSS in your HTML file. You have two options:

1. **Download or Import the CSS file**:
   - **Download**: Download the CSS file from [here](https://unpkg.com/@zumer/orbit@latest/dist/orbit.css) and link it in your HTML file:
     ```html  wrap
     <head>
       <link rel="stylesheet" href="path/to/orbit.css">
     </head>
     ```
   - **Import**: Add the following to your stylesheet:
     ```css wrap
     @import url('path/to/orbit.css');
     ```

2. **Include via CDN**:
   - Add this to your HTML file:
     ```html wrap
     <head>
       <link rel="stylesheet" href="https://unpkg.com/@zumer/orbit@latest/dist/orbit.css">
     </head>
     ```

### Step 2: Include Orbit JavaScript (Recommended)

If you plan to use additional features like radial progress bars, curved text, and slices, include Orbit's JavaScript. You can do this in two ways:

1. **Download the JavaScript file**:
   - Download from [here](https://unpkg.com/@zumer/orbit@latest/dist/orbit.js).
   - Link it in your HTML file:
     ```html  wrap
     <head>
       <script src="path/to/orbit.js" defer></script>
     </head>
     ```

2. **Include via CDN**:
   - Add this to your HTML file:
     ```html wrap
     <head>
       <script src="https://unpkg.com/@zumer/orbit@latest/dist/orbit.js" defer></script>
     </head>
     ```

### Step 3: Set up Orbit layout

Now, create a container with the `gravity-spot` class, and within it, add a radial layout using the `orbit` class. Inside the `orbit`, add radial elements, such us: `satellite` class or `o-text` web component . Here’s a minimal working example:

```html wrap
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="/path/to/orbit.css" />
    <script src="/path/to/orbit.js" defer></script> <!-- Only if using additional features -->
    <title>Orbit Quick Start</title>
  </head>
  <body>
    <div class="bigbang">
      <div class="gravity-spot">
        <div class="orbit">
          <div class="satellite">1</div>
          <div class="satellite">2</div>
          <div class="satellite">3</div>
        </div>
        <div class="orbit">
          <o-text>Curved text</o-text>
        </div>
      </div>
    </div>
  </body>
</html>
```

### Step 4: Install via Package Manager (Optional)

You can also install Orbit using npm or yarn for easier management in your project:

```sh 
npm install @zumer/orbit
```

## Next steps

Congratulations! You have successfully integrated Orbit into your project. Now, you can explore more advanced features and customization options. Check out the full documentation for detailed guides and examples. 

Happy coding!

