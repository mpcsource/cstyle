![CStyle Logo](https://github.com/mpcsource/cstyle/blob/210884511f78e4f122af9307022753b3277f7db5/dist/logo.png)

# CStyle: A CSS Framework

### Installation:

Simply add this to your HTML head before any other CSS:
```
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/mpcsource/cstyle@main/dist/css/cstyle.min.css">
```

### How to use:

The page is divided into components of HTML that we'll call containers. This framework is based on HTML div's to make everything prettier and more organized.

So first you create a ```<div>``` with a ```cont``` class, and then you start giving it more classes, which I am going to list below!
  
## Full Documentation:

### ```cont```
> A container for every other element.

### Main colors
* Default,
* Error,
* Alarm,
* Link,
* Moon,
* Dark

### Secondary colors
* Gray1,
* Gray2

### Navbars
```
<div class="cont">
      <div class="navdiv bg-moon">
          <div class="navtitle">Brand Name</div>
          <div class="navitem-cont">
              <div class="navitem">
                  <a href="#">Option 1</a>
              </div>
              <div class="navitem">
                  <a href="#">Option 1</a>
              </div>
              <div class="navitem">
                  <a href="#">Option 1</a>
              </div>
          </div>
      </div>
</div>
```
### ```navdiv```
> Container for all of the navbar.

### ```navdiv-center```
> You can use this instead of ```navdiv```to get a centered navbar.

### ```navtitle```
> The brand name or the title of the navbar.

### ```navitem-cont```
> Container for all other options in the navbar, besides the brand name.

### ```navitem```
> Each option/item of the navbar that isn't the title.

### Backgrounds and text colors
> You can use ```bg-ANYCOLORABOVE``` or ```color-ANYCOLORABOVE``` to get a background or a text color.
> ```
> <div class="cont bg-alarm">
>     <h1 class="color-alarm">Hello</h1>
> </div>
> ```

### Text and box shadows
> You can use ```textshadow-1/2/3/4/5``` or ```boxshadow-1/2/3/4/5``` to get a text or box shadow with an intensity from 1 to 5.
> ```
> <div class="boxshadow-3">
>     <h3 class="textshadow-2">Hello World!</h3>
> </div>
> ```

### Margin and padding
> Use ```mg-1/2/3/4/5``` or ```pd-1/2/3/4/5``` to get margin or padding with and intensity from 1 to 5.
> You can also add the direction of the margin or padding by adding ```mg-DIRECTION-1/2/3/4/5```.
> ```
> <div class="cont mg-bottom-5">
>     <div class="pd-1"></div>
> </div>
> ```

### Positions
> Use .POSITION to get a CSS position for your element.
> ```
> <div class="static"></div>
> ```
