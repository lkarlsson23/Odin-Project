# HTML and CSS
- HTML is raw data, text/links/cards/lists/buttons
    - Adds structure to the website
- CSS adds style, positions, color, appearance

# HTML Elements and Tags
- <> Element </>
    - Elements are containers for content
    - Opening and closing tags tell the browser what content the element contains
    - An HTML tag defines the start and end of elements
    - Three main parts, opening tag - content - closing tag

# HTML Boilerplate
- All HTML has the same basic structure
- HTML Sections
    - DOCTYPE - Describes version of HTML to render the document
    - HTML Element - <html lang="en"> </html> Contains everything else
    - Head element - put important meta-information about our webpages, nothing should go inside this that displays content
    - Charset Meta Element "<meta charset="utf-8">", ensures that the webpage will display special symbols and characters
    - Title element, displays in webpage's browser tab
    - Body element, all content that will be displayed to users
        - Always below the head element


# Working With Text
- Paragraph: <p> 
- Heading: <h>
- Strong (bold) </strong>
- Em (italic) <em>
- Comments <!-- -->

# Lists
- Unordered List:
    - <ul> with each item having a <li> element </ul>
- Ordered List:
    - <ol> with each item having a <li> element </ul>

# Links and Images
To create a link in HTML we use the anchor element
- Done by wrapping the text/HTML element with an <a> tag
- Destination for anchor tag = HTML attribute
    - Gives additional information to an HTML element, goes in element's opening tag

Two kinds of links: Absolute and Relative 
## Absolute
- Absolute links are links to pages on other websites
    - This link will always contain the protocol and domain of the destination
## Relative 
- Relative links are links to other pages within our own website
    - Here the domain name is assumed, only the file path is included in the link

# Images
- Images use the <img> tag
- this tage is self closing
    - <img src = "link/path to image">