# Web static

## Inline styling  

Write an HTML page that displays a header and a footer

Layout:

* Body:
  * no margin
  * no padding
* Header:
  * color #FF0000 (red)
  * height: 70px
  * width: 100%
* Footer:
  * color #00FF00 (green)
  * height: 60px
  * width: 100%
  * text `Best School` center vertically and horizontally
  * always at the bottom at the page

Requirements:

* You must use the header and footer tags
* You are not allowed to import any files
* You are not allowed to use the style tag in the head tag
* Use inline styling for all your tags

## Head styling  

Write an HTML page that displays a header and a footer by using the style tag in the head tag

Requirements:

* You must use the header and footer tags
* You are not allowed to import any files
* No inline styling
* You must use the style tag in the head tag

## CSS files

Write an HTML page that displays a header and a footer by using CSS files

Requirements:

* You must use the header and footer tags
* No inline styling
* You must have 3 CSS files:
  * styles/2-common.css: for global style (i.e. the body style)
  * styles/2-header.css: for header style
  * styles/2-footer.css: for footer style
* The layout must be exactly the same as 1-index.html

## Zoning done

Write an HTML page that displays a header and footer by using CSS files

Layout:

* Body:
  * no margin
  * no padding
  * font color: #484848
  * font size: 14px
  * font family: Circular,"Helvetica Neue",Helvetica,Arial,sans-serif;
  * icon in the browser tab
* Header:
  * color #FFFFFF (white)
  * height: 70px
  * width: 100%
  * border bottom 1px #CCCCCC
  * logo align on left and center vertically (20px space at the left)
* Footer:
  * color #FFFFFF (white)
  * height: 60px
  * width: 100%
  * border top 1px #CCCCCC
  * text `Best School` center vertically and horizontally
  * always at the bottom at the page

Requirements:

* No inline style
* You are not allowed to use the img tag
* All images must be stored in the images folder
* You are not allowed to use the style tag in the head tag
* You must have 3 CSS files:
  * styles/3-common.css: for the global style (i.e body style)
  * styles/3-header.css: for the header style
  * styles/3-footer.css: for the footer style

## Search

Write an HTML page that displays a header, footer and a filters box with a search button.

Layout:

* Container:
  * between header and footer tags, add a div:
    * classname: container
    * max width 1000px
    * margin top and bottom 30px - it should be 30px under the bottom of the header
  * center horizontally
* Filter section:
  * tag section
  * classname filters
  * inside the .container
  * color white
  * height: 70px
  * width: 100% of the container
  * border 1px #DDDDDD with radius 4px
* Button search:
  * tag button
  * text Search
  * font size: 18px
  * inside the section filters
  * background color #FF5A5F
  * text color #FFFFFF
  * height: 48px
  * width: 20% of the section filters
  * no borders
  * border radius: 4px
  * center vertically and at 30px of the right border
  * change opacity to 90% when the mouse is on the button

Requirements:

* You must use: header, footer, section, button tags
* No inline style
* You are not allowed to use the img tag
* You are not allowed to use the style tag in the head tag
* All images must be stored in the images folder
* You must have 4 CSS files:
  * styles/4-common.css: for the global style (i.e body and .container styles)
  * styles/3-header.css: for the header style
  * styles/3-footer.css: for the footer style
  * styles/4-filters.css: for the filters style
* 4-index.html won’t be W3C valid, don’t worry, it’s temporary

## More filters

Write an HTML page that displays a header, footer and a filters box.

Layout:

* Locations and Amenities filters:
  * tag: div
  * classname: locations for location tag and amenities for the other
  * inside the section filters (same level as the button Search)
  * height: 100% of the section filters
  * width: 25% of the section filters
  * border right #DDDDDD 1px only for the first left filter
  * contains a title:
    * tag: h3
    * font weight: 600
    * text States or Amenities
  * contains a title:
    * tag: h4
    * font weight: 400
    * font size: 14px
    * text with fake contents

Requirements:

* You must use: header, footer, section, button, h3, h4 tags
* No inline style
* You are not allowed to use the img tag
* You are not allowed to use the style tag in the head tag
* All images must be stored in the images folder
* You must have 4 CSS files:
  * styles/4-common.css: for the global style (i.e body and .container styles)
  * styles/3-header.css: for the header style
  * styles/3-footer.css: for the footer style
  * styles/5-filters.css: for the filters style
