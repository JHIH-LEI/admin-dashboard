This project does not follow the mobile-first principle because the goal of this homework was to practice using CSS Grid and Flexbox. 
The project is based on [this tutorial from The Odin Project](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-admin-dashboard).

Here’s a brief overview of my approach:

Initial Layout:
I began by annotating the design image with boxes and comments to help visualize and plan the structure of the HTML.
HTML Structure:
Next, I completed the HTML layout, ensuring the structure matched the design.
Component Layout:
I then worked on laying out the overall components, followed by focusing on each individual component layout. Once all components were positioned, I moved on to refining the typography and other text-related styles.
Fluid Design:
Additionally, I experimented with CSS clamp() for creating a fluid design that adapts to different view points.

Here’s the final result:

[demo](https://jhih-lei.github.io/admin-dashboard/)
<br>
<img width="2041" alt="螢幕截圖 2024-11-12 上午11 22 48" src="https://github.com/user-attachments/assets/7d7dfbc3-9b0d-47d6-8496-512b8d615fa4">

## Web Accessibility Improvements:
1. Utilized semantic landmarks to enhance navigation and improve content recognition for screen readers and assistive technologies.
2. Implemented a hidden skip link to enable better keyboard navigation, allowing users to quickly skip to the main content.

## Web Performance Improvements:
1. using WebP image format as first choice, also added fallback for browsers that do not support WebP format.
   Result by lighthouse

   ### Before:
   <br>
   <img width="577" alt="螢幕截圖 2024-11-12 上午11 08 45" src="https://github.com/user-attachments/assets/202041eb-77fb-4f83-b1ad-9aa2d397073c">
   <br>

   ### After:
   <br>
   <img width="750" alt="螢幕截圖 2024-11-12 上午11 19 36" src="https://github.com/user-attachments/assets/afb73255-d015-4e10-bc70-0b1f12142292">
