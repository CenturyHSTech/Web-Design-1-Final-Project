# Image Gallery Project
Put your html and css files in here.

## Goal:
Students will code and design an image gallery project that contains a minimum of 9 related thumbnail-sized images that when clicked open up a full-sized version of those images. The design of the layout should be a grid of images that are styled using fonts, colors, borders, and other styles.

## Requirements
### Folder and file structure requirements
* Create a single web page named `index.html`
* Create a folder titled, `images` (all lowercase letters)
* at least 18 images in all (each stored in the images folder)
  *  at least 9 full-sized images
  *  at least 9 thumbnail (cropped and resized to no wider than 450px) 
    + one for each of the full-sized images

### HTML requirements
*  Four or more HTML files with:
  *  All standard HTML5 tags (`DOCTYPE`, `html`, `head`, `title`, `body`)
  *  A `nav` element with an `ul` that contains one `li` for each page in the navbar.
    + each `li` must contain an `a` that links (relative link) to each `html` doc.
  *  A `header` with a `h1` title (you may wish to put the `h1` in an `hgroup` inside that `header`)
  *  A `main` section to contain the primary content for each page.
  *  Each page should include 2-3 or more **containing elements** (`section`, `article` or `div` tags -*  I'll let you chose)
    + Include a minimum of 8 such containers in all.
    + Each should include a section header using the `h2` tag and other HTML content, such as lists, paragraphs, links, tables.
  *  Each page should also include one or more `figure` elements that contain an image and a `figcaption` to caption the image.

### Validity Requirements
* No HTML errors (this will be tested in the validator tests)
* No CSS errors (this will be tested in the validator tests)

### CSS Requirements
*  Use at least one external stylesheet that all pages link to.
*  All pages should be consistent one from another, unless it's a relatively minor change, such as a different background image on the banner
    *  **NOTE**: only use the `style` tag for a minor override. Most styles belong in the external stylesheet.
*  Font pairing
*  Background and text colors with proper contrast:
  *  AAA rating for body text
  *  AA rating acceptable for headings
*  Use `flex` or `grid` layout for the `ul` in the `nav` and the content in the `main` element.
*  Style `figure` elements with `margin`, `border`, `padding`, and `background-color`

### Design Requirements
* Content must be visible and readable (with high contrast)
* Images are all related in some way (through topic or theme)
* Fonts, colors, and any other styling is consistent with the theme of the images
* Layout is fluid and works on any browser/viewport width

### Assignment Submission Requirements
* Student must commit and push their changes to the repo (repo has the latest work)
* Layout should not look broken at any width
* No horizontal scrollbars should appear unless the window is more narrow that a single figure
* Student must record their image gallery at various viewport widths (or zoom levels) *  best will go towards a video showing the browser being set to different screen widths.