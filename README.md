**Responsive Cyberpunk Network Animation**

A clean, responsive, and animated SVG background designed to represent an abstract "mind map" or tech network. It features a sophisticated split-screen effect for wide desktop views that fluidly adapts to a single, focused composition on mobile devices. All animations are powered by pure CSS for optimal performance and a sharp cyberpunk aesthetic.

This template is ideal for hero sections, banners, or decorative backgrounds on tech-focused websites, portfolios, or futuristic projects.

Features
Abstract Network Design: Visually complex line work and nodes create an engaging, non-literal "mind map" or network aesthetic, perfect for conveying concepts of data, connectivity, or complexity.

True Cyberpunk Aesthetic: A high-contrast color palette of dark backgrounds, glowing cyan, and vibrant magenta creates a distinct, modern tech feel.

Split Desktop View: Presents an immersive, wide background for large screens.

Smart Mobile View: On smaller screens, the layout gracefully reframes the artwork to a single, centered vertical composition, ensuring a polished look on any device.

Pure CSS Animations: Smooth line drawing, subtle glowing effects, and staggered fade-ins are all handled with efficient CSS keyframes.

Ready to Customize: Provided as a single index.html file, ready for you to drop in your own SVG artwork if desired.

How to Use

This template is built around a two-SVG structure to achieve its split-screen desktop and responsive mobile layout. While the included SVGs are ready to use out-of-the-box, you can replace them with your own wide graphic by following these steps:

Prepare Your Wide SVG:

Design your graphic as a single, wide SVG (e.g., in Illustrator, Figma, or Inkscape). A size of roughly 1386px wide by 693px tall is a good starting point.

Organize your artwork into two main groups, one for the left half and one for the right.

Split Your SVG into Two Files:

Create a new SVG file for the left half. Set its viewBox to 0 0 693 693 (or half the width of your original). Copy the artwork from the left half of your design into this file.

Create a new SVG file for the right half. Set its viewBox to 693 0 693 693. Copy the artwork from the right half of your design into this file, ensuring the coordinates are adjusted to be relative to this new viewBox.

Update the index.html:

Open the provided index.html file.

Replace the content inside <svg class="left-svg">...</svg> with the code from your prepared left-half SVG file.

Replace the content inside <svg class="right-svg">...</svg> with the code from your prepared right-half SVG file.

Adjust the viewBox, width, and height attributes on the <svg> tags to match your artwork.
Customize Mobile View (Optional):

In the <style> block, find the @media screen and (max-width: 768px) query.

You may need to adjust the viewBox property for the .left-svg here to best frame your new graphic on smaller screens.
License

This project is open-source and available under the Apache License 2.0. You are free to use, modify, and distribute it for any purpose, including commercial projects.
