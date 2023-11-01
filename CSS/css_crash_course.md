# CSS
Cascading Stylesheets
[Back at it again with Traversy Media.](https://www.youtube.com/watch?v=yfoY53QXEnI)

Many ways to do the same things.
**NOT** covering flexbox, animation, etc. (need to go back and add some of this I think).

Can be extended with Sass/Less

### 3 Methods for Adding CSS
1. Inline CSS: Directly in the HTML element (No!)
2. Internal CSS: Using `<style>` tags within a single document
3. External CSS: Linking an external .css file

## CSS Selectors
Many parts to the selector:
- Selector
- Declaration start
- property
- value
- property/value separator
- value
- end with semi-colon
- declaration end

### Colors in CSS
Can use:
- Color Names ('red')
- HTML5 Color Names ('coral') 
- Hexadecimal (#f4f4f4)
- RGB rgb(0,0,255)

### Web Safe Fonts
Can use without any special installation

### difference between class and id
ID = unique -- won't be used anywhere else (targeted with a "#")
Class = non-unique -- could be used again elsewhere (targeted with a '.')
*bootstrap doesn't use ids*

### Box Model
layered starting at:
1. content
2. padding
3. border
4. margin

### Styling
You can target the font, the text, letter spacing, word spacing, and much more. to make it look the way you want to.

#### in-line vs. block
in-line puts things on the same line, block takes up the whole width of the page

### Positioning in CSS
- Static: the default, renders the elements in the order of the document flow
- Relative: relative to it's normal positionfalls naturally to it's natural position, but can add 'top', 'left', 'bottom' etc.
- Absolute: allows us to target whatever position we want within a relative position
- Fixed: always in the same position
- Initial: restores the default
- Inherit: inherits from its parent element

### Responsive Design
You can adjust the sizing of elements to percentages which will allow the screen to determine how large certain elements end up being. You can also use media queries to get the screen size of the browser you will be viewing on and that can establish parameters for your CSS to adjust as needed to best fit a screen that may not be the same dimensions as the ones used to create the website in the first place.