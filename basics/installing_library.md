---
layout: page
---
## Libraries (or 'packages')

Remember the movie 'The Matrix'. With Keanu Reaves?
Remeber how in that world, in order to learn skills, they just get downloaded into your brain through that big plug in the back of your skull?


[![](files/0.jpg)](https://www.youtube.com/watch?v=6vMO3XmNXe4)

R is kind of like that. Not that that's how you learn R, but that's how R learns new things. R is capable of acquiring new capabilities, beyond what's possible with the basic installation ('base') of R. These new capabilities get downloaded into your R program as 'packages' or 'libraries'. These packages live in an online repository called CRAN. (Acutally there are lots of these repositories, but thats for another day.) You get these into R by first downloading them (with the command `install.packages("PACKAGE_NAME_HERE")`) and then loading it into your R session (`library(PACKAGE_NAME_HERE)`).

<a href="https://imgflip.com/i/1tl4y5"><img src="https://i.imgflip.com/1tl4y5.jpg" title="made at imgflip.com"/></a>

R has an enormous ecosystem of libraries (number in the tens of thousands) for various data-analysis tasks, ranging from the simple to the very sophisticated. 

The first minute of [this video](https://www.youtube.com/watch?v=u1r5XTqrCTQ) gives a walk-through, but we'll walk through the steps here, too.  Conveniently, packages, can be installed from within RStudio itself.   

### Installing a library from within RStudio

Launch RStudio, and find the row of tabs for Files, Plots, Packages, etc.  You can see this on the upper-right panel in the figure below.

![](files/packages_tab.png)

Click on the Packages tab, and then on the button in the row just beneath it that says "Install".  You should see a window pop up that looks like the one below.  Type "mosaic" into the field where it says "Packages."  

![](files/install_mosaic.png)

RStudio may autocomplete the available packages that begin with the string you've typed in.  If so, select "mosaic" from the list that appears.  IMPORTANT: make sure that the box next to "Install dependencies" is checked (as it is in the picture above).  If it isn't, check it.

Click the Install button.  Now a bunch of text will get dumped to the Console window, like this:

![](files/installation_echo.png)

This indicates that the mosaic library (and several other libraries upon which it depends) are being installed.

It's possible that RStudio will give you a prompt like the following:

![](files/compilation.png)

If so, just type "n" for no, and hit Enter to continue.

Eventually you will see that text has stopped appearing in the console, and that you have a blinking cursor next to a caret mark (>).  When this happens, the mosaic package has been installed, and is now available to be loaded and used.


