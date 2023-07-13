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

### box model
layered starting at:
1. content
2. padding
3. border
4. margin