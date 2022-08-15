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

## Display results

Write an HTML page that displays a header, footer, a filters box with dropdown and results.

Layout:

* Add Places section:
  * tag: div
  * tag: section
  * classname: places
  * same level as the filters section, inside .container
  * contains a title:
    * tag: h1
    * text: Places
    * align in the top left
    * font size: 30px
  * contains multiple “Places” as listing (horizontal or vertical) describe by:
    * tag: article
    * width: 390px
    * padding and margin 20px
    * border #FF5A5F 1px with radius 4px
    * contains a title:
      * tag: h2
      * font size: 30px
      * center horizontally

Requirements:

* You must use: header, footer, section, article, button, h1, h2, h3, h4, ul, li tags
* No inline style
* You are not allowed to use the img tag
* You are not allowed to use the style tag in the head tag
* All images must be stored in the images folder
* You must have 5 CSS files:
  * styles/4-common.css: for the global style (i.e. body and .container styles)
  * styles/3-header.css: for the header style
  * styles/3-footer.css: for footer style
  * styles/6-filters.css: for the filters style
  * styles/7-places.css: for the places style

## More details

Write an HTML page that displays a header, a footer, a filter box (dropdown list) and the result of the search.

Layout:
Add more information to a Place article:

* Price by night:
  * tag: div
  * classname: price_by_night
  * same level as the place name
  * font color: #FF5A5F
  * border: #FF5A5F 4px rounded
  * min width: 60px
  * height: 60px
  * font size: 30px
  * align: the top right (with space)
* Information section:
  * tag: div
  * classname: information
  * height: 80px
  * border: top and bottom #DDDDDD 1px
* contains (align vertically):
  * Number of guests:
    * tag: div
    * classname: max_guest
    * width: 100px
    * fake text
    * icon
    * font size: 30px
  * Number of bedrooms:
    * tag: div
    * classname: number_rooms
    * width: 100px
    * fake text
    * icon
  * Number of bathrooms:
    * tag: div
    * classname: number_bathrooms
    * width: 100px
    * fake text
    * icon
* User section:
  * tag: div
  * classname: user
  * text Owner: `<fake text>`
  * Owner text should be in bold
* Description section:
  * tag: div
  * classname: description

Requirements:

* You must use: header, footer, section, article, button, h1, h2, h3, h4, ul, li tags
* No inline style
* You are not allowed to use the img tag
* You are not allowed to use the style tag in the head tag
* All images must be stored in the images folder
* You must have 5 CSS files:
  * styles/4-common.css: for the global style (i.e. body and .container styles)
  * styles/3-header.css: for the header style
  * styles/3-footer.css: for the footer style
  * styles/6-filters.css: for the filters style
  * styles/8-places.css: for the places style

## Full details

Write an HTML page that displays a header, footer, a filters box with dropdown and results.

Layout:
Add more information to a Place article:

* List of Amenities:
  * tag: div
  * classname: amenities
  * margin top 40px
  * contains:
    * title:
      * tag h2
      * text Amenities
      * font size 16px
      * border bottom #DDDDDD 1px
    * list of amenities:
      * tag ul / li
      * no list style
      * icons on the left: Pet friendly, TV, Wifi, etc… feel free to add more
* List of Reviews:
  * tag: div
  * classname: reviews
  * margin top 40px
  * contains:
    * title:
      * tag h2
      * text Reviews
      * font size 16px
      * border bottom #DDDDDD 1px
    * list of amenities:
      * tag ul / li
      * no list style
      * a review is described by:
        * h3 tag for the user/date description (font size 14px). Ex: “From Bob Dylan the 27th January 2017”
        * p tag for the text (font size 12px)

Requirements:

* You must use: header, footer, section, article, button, h1, h2, h3, h4, ul, li tags
* No inline style
* You are not allowed to use the img tag
* You are not allowed to use the style tag in the head tag
* All images must be stored in the images folder
* You must have 5 CSS files:
  * styles/4-common.css: for the global style (i.e. body and .container styles)
  * styles/3-header.css: for the header style
  * styles/3-footer.css: for the footer style
  * styles/6-filters.css: for the filters style
  * styles/100-places.css: for the places style
