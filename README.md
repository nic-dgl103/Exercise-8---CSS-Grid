# CSS Grid

## Objectives

Create a unique web layout using CSS Grid that showcases your understanding of how to combine Flexbox and Grid to organize and position content. You will also create and style some unique content to populate the different areas of the page.

## Instructions

### 1. Get set up

1. Clone your remote exercise repository onto your local machine.
2. Create a new a CSS file and link it to the index.html file.

_Tip: Read all the instructions and then sketch the layout and content of your page before you start to code. This will help you visualize how you want the content to be arranged and will help ensure that your layout meets all the requirements in the instructions._

### 2. Create the grid structure

In your stylesheet, set the display property of the body element to grid.
Define the grid layout using:

- grid-template-columns to create a column structure.
- grid-template-rows to create a row structure.
- grid-template-areas to visually organize the layout and assign areas for each element.
- the repeat() function if/where appropriate to simplify your column definitions.

### 3. Add HTML content to each cell

1. Header: Add a logo image and create a navigation bar with links to different sections of your site (e.g., Home, About, Services, Contact).
2. Main: Include at least two section elements with content such as headings, paragraphs, lists, and at least one relevant image. Each section will have a unique layout.
3. Aside: This could include related articles, advertisements, or additional resources that might interest the reader. Include content such as headings, paragraphs, lists, links, at least one relevant image, and article elements if appropriate.
4. Footer: Provide contact information (such as an email address or phone number), links to social media profiles, and additional navigation links.

### 4. Style the layout

Style the page to ensure that the design is visually well-ordered and easy to read, reflecting attention to detail:

- Apply a grid-gap to create clear separation between grid items, preventing elements from crowding each other.
- Use background colors strategically to differentiate areas without being overly distracting. Choose a cohesive color palette to maintain a polished and unified appearance.
- Add appropriate padding and margins to create enough breathing room around the content, ensuring that the layout feels balanced and uncluttered.
- Ensure that the layout is flexible by using relative units like fr, %, and rem for grid items and their content. Small box model dimensions can use the px unit. This helps the layout adapt to different screen sizes and user/browser preferences.
- Implement Flexbox inside at least 2 grid cells for additional layout control. For example, you might use Flexbox to:
  - Center content within a section (vertically and/or horizontally).
  - Evenly space navigation links, images or other elements for clean, structured alignment.
- Apply typographic CSS properties to help make the content easy to read.

### 5. Format, organize and add comments

- Use the Prettier VSCode extension to format HTML and CSS code.
- Add organizational CSS comments and order your style rules so that your CSS is easy to read.
- Add a few comments to explain your HTML and CSS code and highlight anything of interest.

### 6. Check for errors

- Use the VSCode HTMLHint extension and validate your HTML code to make sure that it is correct: https://validator.w3.org/#validate_by_upload. Take a screenshot of the results.
- Validate your CSS code to make sure that it is correct: https://jigsaw.w3.org/css-validator/ for CSS. Take a screenshot of the results.

**You have now completed your exercise but you still need to push your edits to GitHub and submit it in Brightspace. Make sure to follow the instructions in the How to Complete Your Exercises Guide.**
