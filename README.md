
# Image Gallery Project

This project involves designing and coding an image gallery that displays a minimum of 9 thumbnail images. Each thumbnail links to a full-sized version, and the layout should be responsive and visually styled.

---

<details>
<summary><strong>Project Overview</strong></summary>

Students will represent multi-page websites as separate files with shared content across pages, using appropriate file naming, directory structure, and version control.

Students should be able to:
* employ HTML code to mark up text and create a multi-file web site.
* Use HTML and CSS to create a navbar that links multiple files together.
* Re-use and modify existing code to design a layout for the page

</details>

---
<details>
<summary><strong>Setup Instructions</strong></summary>

1. Clone this project by clicking the green `Code` button and choosing Open with GitHub Desktop.
2. Choose the "for my own purposes" option (the 2nd choice).
3. Open this project in VS Code.
4. Put all project files in the `project` folder.
5. Create a folder for your images and name it `images` (this is where you put your images).
6. Review the requirements below and any other instructions your teacher provides (in Google Classroom).
7. Commit and push your changes at least once or twice during each work session.
8. Check the tests on GitHub.

### Getting any errors?
#### Validation Errors: 
If you get any validation errors, try checking your code using the [HTML Validator](https://validator.w3.org/nu/#textarea) for HTML errors or the [CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_upload).

#### Color Contrast Errors:
If you are getting any color contrast errors, there are a few things to check:
* ***Did you only set the `color` or `background-color` and not the other?*** Any time you set a color or background color, be sure to add both in the same declaration block.
* Check both color and background color using the [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)

</details>

---

<details>
<summary><strong>Project Requirements</strong></summary>

### Content
You may either...
- Choose one of the following options from the [https://github.com/CenturyHSTech/Website-Project-Content-Repository](https://github.com/CenturyHSTech/Website-Project-Content-Repository):
  + Pixel Playground
  + Regional Chinese Food
  + Skyhaven Roofing Company
  + Ultimate Steak Cooking Guide
NOTE: you might have to just download a zip version of the file.

OR just choose your own topic 

### Folder and File Structure
- Create a home page and name it `index.html`
- Create 3 or 4 other pages using the same HTML structure and styles as the home page
- Create a folder titled `images` (all lowercase) for any image you use
- Include at least 6 images
- Create one or more external stylesheets for your styles, but do not use the style tag unless you want one specific change to a given page

***IMPORTANT*** all shared styles (which should be almost if not all of your styles) must be in one or more external stylesheets and linked in the `head` element of all `html` docs

### HTML Requirements
- Four or more HTML files with:
  - All standard HTML5 tags (`DOCTYPE`, `html`, `head`, `title`, `body`)
  - A `nav` element with an `ul` that contains one `li` for each page in the navbar.
    + each `li` must contain an `a` that links (relative link) to each `html` doc.
  - A `header` with a `h1` title (you may wish to put the `h1` in an `hgroup` inside that `header`)
  - A `main` section to contain the primary content for each page.
  - Each page should include 2-3 or more **containing elements** (`section`, `article` or `div` tags -- I'll let you chose)
    + Include a minimum of 8 such containers in all.
    + Each should include a section header using the `h2` tag and other HTML content, such as lists, paragraphs, links, tables.
  - Each page should also include one or more `figure` elements that contain an image and a `figcaption` to caption the image.

### CSS Requirements
- Use at least one external stylesheet that all pages link to.
- All pages should be consistent one from another, unless it's a relatively minor change, such as a different background image on the banner
    - **NOTE**: only use the `style` tag for a minor override. Most styles belong in the external stylesheet.
- Font pairing
- Background and text colors with proper contrast:
  - AAA rating for body text
  - AA rating acceptable for headings
- Use `flex` or `grid` layout for the `ul` in the `nav` and the content in the `main` element.
- Style `figure` elements with `margin`, `border`, `padding`, and `background-color`

### Design Requirements
- High contrast and readability
- Thematically consistent images and styling
- Responsive layout that works across all screen sizes

### Validity Requirements
- No HTML or CSS errors (validated via W3C tools)

</details>

---

<details>
<summary><strong>Submission Requirements</strong></summary>

- All changes must be committed and pushed to the repository
- Submit a recording showing the gallery at various viewport widths
- I will be looking for the following design recommendations:
    + your ***layout remains intact*** at all screen widths
    + there are ***no horizontal scrollbars*** (unless the screen is narrower than a single figure)
</details>

---
