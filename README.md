```markdown
# Photography Exhibit Layout using Tailwind CSS

## Overview
This project creates a responsive photography exhibit layout styled with Tailwind CSS utility classes. The layout displays a grid of three photo cards, each featuring an image, a subheading, and a description. This example demonstrates how to use Tailwind's utility classes to build a clean, modern, and responsive gallery.

## Features
- CSS Grid layout with fixed number of columns
- Gap spacing between grid items
- Responsive images with rounded borders
- Styled subheadings and descriptions
- Customizable card styles for a unique personal style

## Live Preview
*(Insert a screenshot or link to a live demo if available)*

## Usage

### Prerequisites
- Basic understanding of HTML
- Tailwind CSS included in your project

### Setup
1. Ensure Tailwind CSS is added to your project. You can include Tailwind via CDN:

```html
<!-- Add this inside your <head> in your HTML file -->
<link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
``

2. Copy the following HTML structure into your project:

```html
<div class="main-container grid grid-cols-3 gap-4 gap-y-6 p-6">
  <!-- Card 1 -->
  <div class="card border rounded-lg p-4 shadow-lg">
    <img src="https://cdn.freecodecamp.org/curriculum/labs/colosseo.jpg" alt="Ancient Colosseum" class="rounded mb-4 w-full h-auto" />
    <div class="subheading font-semibold text-xl mb-2">Ancient Colosseum</div>
    <div class="description text-sm">A stunning view of the historic Roman amphitheater, capturing its majestic architecture.</div>
  </div>
  
  <!-- Card 2 -->
  <div class="card border rounded-lg p-4 shadow-lg">
    <img src="https://cdn.freecodecamp.org/curriculum/labs/alps.jpg" alt="Snowy Alps" class="rounded mb-4 w-full h-auto" />
    <div class="subheading font-semibold text-xl mb-2">Snowy Alps</div>
    <div class="description text-sm">Majestic mountains covered in snow, perfect for adventure and nature lovers.</div>
  </div>
  
  <!-- Card 3 -->
  <div class="card border rounded-lg p-4 shadow-lg">
    <img src="https://cdn.freecodecamp.org/curriculum/labs/sea.jpg" alt="Serene Sea" class="rounded mb-4 w-full h-auto" />
    <div class="subheading font-semibold text-xl mb-2">Serene Sea</div>
    <div class="description text-sm">A calming shot of the sea, emphasizing tranquility and natural beauty.</div>
  </div>
</div>
``

### Customization
- Change images by updating the `src` attribute.
- Modify text content in `.subheading` and `.description`.
- Adjust the grid layout by changing `grid-cols-3` to another number.
- Style the cards further with additional Tailwind classes or custom CSS.

## License
This project is for educational purposes. Feel free to customize and expand it!

## Contact
*(Your Name or Contact Info)*

---

Happy coding! 🎨📸
```
