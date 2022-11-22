these practical challenge helps me to practice how to set a resolution switching image according to the screen sizes
so we have given two diffrent images 1x and 2x for small and wider screens so whenever the screen size changes from 750px the image we provide will be changed automatically!
these is how it is done

````html
<picture>
  <source srcset="images/product@1x.jpg 750w, images/product@2x.jpg 1200w" />
  <!--!important for screens <750px and <1200px--->
  <img src="images/product@2x.jpg" />
</picture>

beside the card grid layout will be change from 1x2 to 2x1 for mobile versions !
and also it have something to practice on text-decoration property for price tag
we must put line-through and the thickness should be very thin ```html
<div class="old__price">
  <h2 class="old__price__tag">$169.99</h2>
</div>
```css .old__price__tag { font-weight: 400; text-decoration-line: line-through;
text-decoration-thickness: 0.1em; }
````
