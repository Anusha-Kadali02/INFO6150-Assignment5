# INFO6150-Assignment5

# My Website
<ul>
  <li>
   Boston Voyages: Explore the rich history, vibrant culture, and hidden gems of Boston through our comprehensive travel guide. Discover the best places to visit, and experience in this iconic city.
  </li>
</ul>

# Grid Layout
<ul>
  <li>Have used grid layout for creating the layout of the webpage and also have used inside footer to create its layout.</li>
</ul>

# Flex Box Layout
<ul>
  <li>Have used flex box for aligning cards in a row and making sure there are only 3 cards in a row, and have used flex for aligning the content inside the nav bar.</li>
</ul>

# SCSS Variables
<ul>
  <li>Have Used SCSS variables to assign standard values for colors to reduce repetition.</li>
</ul>

# Custom Properties
<ul>
  <li>Have used the custom property which is similar to scss varibales for the purpose of defining the color of the text based on the lightness of its background.</li>
</ul>

# Nesting
<ul>
  <li>
    Have used SCSS nesting in many places, for example in cards selector i have nested each card selector, the card title, the card paragraph to write more organized and maintainable styles.
  </li>
</ul>

# Interpolation
<ul>
  <li>
    Have used interpolation to dynamically insert the value of the `$image` variable into the `url()` function. This allows us to easily set the background image for an element and customize its size and repeat properties.
  </li>
</ul>

# Placeholder Selectors
<ul>
  <li>
    %btn is a placeholder selector defining a button style.
  </li>
</ul>

# @mixin
<ul>
  <li>
     Have used mixin to set the background color of an element, to set the font family of an element and to set a background image for an element. Where you can also specify the background size and repeat options.
  </li>
</ul>

# @function
<ul>
    <li>lighten-bg($color, $percentage): This function lightens a given color by a specified percentage. It's useful for adjusting the brightness of colors in your stylesheets.</li>
    <li>set-text-color($color): Use this function to determine the appropriate text color based on the lightness of a background color. If the background color is relatively light, it returns a dark text color; otherwise, it returns a light text color.</li>
<li>rem($pixel): This function converts pixel values to rem values. If you pass a value without units, it will automatically convert it to rems by dividing it by 16. It helps maintain responsive typography in your web projects.</li>
</ul>

# saas:math
<ul>
  <li>
    Have used sass:math module in my code to perform mathematical operations, such as checking for unitlessness and division, which are commonly used in responsive web design when working with rem units.
  </li>
</ul>

# @error
<ul>
  <li>
     Have used @error as a way to communicate an error message to users of my SCSS code when they misuse the function by providing values with units for font size.
  </li>
</ul>

# Relational Operator
<ul>
  <li>
    Have used a relational operator within an @if statement to compare the lightness of a color with a certain threshold.
  </li>
</ul>

# @extend
<ul>
  <li>
    Have used @extend %btn; to inherit the properties defined in the %btn placeholder selector. This allows me to reuse the styles defined in %btn for the .btn-primary class.
  </li>
</ul>

# @import
<ul>
  <li>
    Have used @import directive in SCSS to include the content from other SCSS files into my main SCSS file.
  </li>
</ul>

# Parent Selector
<ul>
  <li>
    Have used parent selecctor in nested selectors to refer to the outer selector. For example have used it inside the buttton class selector so that unique styles will be applied on hover.
  </li>
</ul>
