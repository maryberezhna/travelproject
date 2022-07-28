Hi! Here you can find the open-source travel landing page project. 
Enjoy!


Advices:

We group all CSS properties in different code blocks by its type (what they do), so, in this way, it would be easy to find them. Here is a list of most common groups:
 1 Positioning: position, left/right/top/bottom, float, clear, z-index.
 2 Sizes and indentation: width, height, margin, padding…
 3 Typography: font, color…
 4 Color and style: background, border
 5 General content design: list-style-type, overflow
 6 Mixins: @apply --box-styles, @apply --clear Example:

.some-block { 
  /* Positioning */
  position: absolute; 
  left: 0;
  top: 0;
  /* Sizes and indentations */
  width: 100px;
  height: 100px;
  margin: 10px;
  padding: 0 0 6px 0; 
  /* Typography */
  color: red;       
  font-size: 16px;
  font-style: italic;  
  font-weight: bold;
  /* Color and style */
  background: #fff;
  border: 1px solid #fff;
  /* General content design */
  overflow: hidden;
  /* Mixins */ 
  @apply --box-styles;
}
