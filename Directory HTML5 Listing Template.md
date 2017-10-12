**Directory** - Listing Templates

Welcome to the *Directory* Listing Templates.


**Directory Template Documentation**

This document covers the installation and use of this theme and often reveals answers to common problems and issues - read this document thoroughly if you are experiencing any difficulties. If you have any questions that are beyond the scope of this document, feel free to pose them in the dedicated support section.

Should anything else be here? Add it (either here or in another page)!


**Features and Functionality**
<ol>
<li>Responsive Design</li>
<li>W3 Validation Code</li>
<li>Build on Bootstrap 3</li>
<li>Retina Ready</li>
<li>Clean & Optimized Code</li>
<li>800+ Font Icons</li>
<li>CSS3 onscroll animation</li>
<li>Fully Responsive Design</li>
<li>All files are well commented</li>
<li>browser Compatible with IE9+, Firefox, Safari, Opera, Chrom</li>
<li>Google map</li>
</ol>


Check out the **[Full Template Features](https://pixelaar.com/)** 


##### Table of Contents

[Getting started](#Getting-started)  
[CSS](#CSS)  
[The JavaScript](#The-JavaScript)  
[Images](#images)  
[Font](#Font)  
[Owlcarousel](#owlcarousel)  
[HTML Structure](#HTML-Structure)  
[Bootstrap](#Bootstrap)   
[Reference link](#Reference-link)  
  
<a name="Getting-started"/>


## Getting started


[Directory - Listing Templates](https://pixelaar.com/) | [Documentation
table of contents](TOC.md)

Basic structure

A basic Directory - Listing Templates site initially looks something like this:

```

├── css
│   ├── animate.min.css
│   ├── bootstrap.min.css
│   ├── font-awesome.min.css
│   ├── jquery.mCustomScrollbar.min.css
│   ├── magnific-popup.css
│   ├── responsive.css
│   ├── sidenav.css
│   └── style.css
├── fonts
├── img
├── js
│   ├── animation-text.js
│   ├── bootstrap.min.js
│   ├── imagesloaded.pkgd.min.js
│   ├── infobox.min.js
│   ├── jquery.easeScroll.js
│   ├── jquery.easing.min.js
│   ├── jquery.mCustomScrollbar.js
│   ├── magnific-popup.min.js
│   ├── maps.js
│   ├── markerclusterer.js
│   ├── scripts.js
│   ├── sidenav.min.js
│   ├── wow.min.js
│   └── vendor
│       ├── html5shim.js
│       ├── modernizr-2.8.1.min.js
│       └── respond.min.js
├── owlcarousel
│   ├── owl.carousel.min.js
│   └── assets
│       ├── owl.carousel.min.css
│       └── owl.theme.default.min.css
├── blog.html
├── blog-details.html
├── 404.html
├── contact.html
├── favicon.png
├── index.html
├── list-details.html
├── list-list-view.html
└── list-list-view-half.html

```

**Directory- Listing Templates**

* [HTML](html.md) — Guide to the default HTML.
* [CSS](css.md) — Guide to the default CSS.
* [JavaScript](js.md) — Guide to the default JavaScript.
* [Installing template](Installin.md) — Guide to the default Installing template.
* [Reference link](Referencelink.md) — Guide to the default Reference link. 

**Related projects**
Tools required for students and teachers

A computer (Linux, Mac or PC will do)

One or more modern web browsers. We'd recommend that you install the latest versions of Opera, Firefox, Safari, Chrome, and Internet Explorer, depending on what is available for your OS.

An internet connection

**A text editor. The free ones we'd recommend are:**

<ol>
<li>Windows: [Notepad++]</li>
<li>Mac: [TextWrangler]</li>
<li>Linux: [BlueFish]</li>
</ol>

**An FTP client. The free ones we'd recommend are:**



<ol>
<li>Windows and Linux: [Filezilla]</li>
<li>Mac: [Cyberduck]</li>

</ol>

Additional tools required for teachers
Example files to demonstrate discussed concepts
An installed server-side testing environment, like [MAMP] or [WAMP] or [XAMPP]

<a name="CSS"/>


## CSS



We are using one primary CSS file for this template: /css/style.css. This file contains all style information for the template .

Use one of the included child themes as a base for further CSS customization.

Styles are being used and test-edit the CSS.
   
   ink rel="stylesheet" href="css/font-awesome.min.css">
   
       <!-- magnific popup css-->
       <link rel="stylesheet" href="css/magnific-popup.css">
   
       <!-- animate css -->
       <link href="css/animate.min.css" rel="stylesheet">
   
   
       <!--owl carousel -->
       <link href="owlcarousel/assets/owl.theme.default.min.css" rel="stylesheet">
       <link href="owlcarousel/assets/owl.carousel.min.css" rel="stylesheet">
   
       <!--custom scroll bar css-->
       <link rel="stylesheet" href="css/jquery.mCustomScrollbar.min.css">
   
       <!-- bootstrap core css -->
       <link href="css/bootstrap.min.css" rel="stylesheet">
   
       <!-- custom css -->
       <link href="css/style.css" rel="stylesheet">
   
       <!-- responsive css -->
       <link href="css/responsive.css" rel="stylesheet">
       
       
<a name="The-JavaScript"/>


## The JavaScript


The JavaScript / jQuery plugins uses are stored in js/ folder. You do not need to edit these items.

The script(s) you can edit as needed are:

js/scripts.js - This contains the plugin setup / init and general information
    
    !-- main jQuery -->
    <script src="js/jquery-3.2.1.min.js"></script>
    
    <!-- bootstrap core js -->
    <script src="js/bootstrap.min.js"></script>
    
    <!-- wow.min.js -->
    <script src="js/wow.min.js"></script>
    
    <!-- smoothscroll -->
    <script src="js/jquery.easeScroll.js"></script>
    
    <!--owl carousel-->
    <script src="owlcarousel/owl.carousel.min.js"></script>
    
    <!--Custom Scroll Bar-->
    <script src="js/jquery.mCustomScrollbar.js"></script>
    
    <!-- scrolling nav -->
    <script src="js/jquery.easing.min.js"></script>
    
    <!--Sidenav js-->
    <script src="js/sidenav.min.js"></script>
    
    <!--animation text js -->
    <script src="js/animation-text.js"></script>
    
    <!--magnific popup js-->
    <script src="js/magnific-popup.min.js"></script>
    
    <!-- custom script -->
    <script src="js/scripts.js"></script>

**scripts.js**


This file can be used to contain or reference your site/app JavaScript code.
If you're working on something more advanced you might replace this file
entirely. That's cool. 

    // ------------------------------------------------------------------
    // jQuery for back to Top
    // ------------------------------------------------------------------

    (function(){

        $('body').append('<div id="toTop"><span>Up</span></div>');

        $(window).scroll(function () {
            if ($(this).scrollTop() != 0) {
                $('#toTop').fadeIn();
            } else {
                $('#toTop').fadeOut();
            }
        });

        $('#toTop').on('click',function(){
            $("html, body").animate({ scrollTop: 0 }, 600);
            return false;
        });

    }());


**plugins.js**


One approach is to put jQuery plugins inside of a `(function($){ ...
})(jQuery);` closure to make sure they're in the jQuery namespace safety
blanket. Read more about 

By default the `plugins.js` file contains a small script to avoid `console`
errors in browsers that lack a `console`. The script will make sure that, if
a console method isn't available, that method will have the value of empty
function, thus, preventing the browser from throwing an error.

**maps**

This file can be used to contain all your website maps such as jQuery plugins and
other 3rd party scripts for a simple site.
 
 
     var map = new google.maps.Map(document.getElementById('map'), {
            zoom: zoomLevel,
            scrollwheel: scrollEnabled,
            center: new google.maps.LatLng(40.80, -73.70),
            mapTypeId: google.maps.MapTypeId.ROADMAP,
            zoomControl: false,
            mapTypeControl: false,
            scaleControl: false,
            panControl: false,
            navigationControl: false,
            streetViewControl: false,
            styles: [{
                "featureType": "poi",
                "elementType": "labels.text.fill",
                "stylers": [{
                    "color": "#747474"
                }, {
                    "lightness": "23"
                }]
            },
## vendor

This directory can be used to contain all 3rd party library code.

Minified versions of the latest jQuery and Modernizr libraries are included by
default. You may wish to create your own.
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.



<a name="0wlcarouse"/>


## Owlcarousel


Information about the default JavaScript included in the project.

**owl.carousel.min.js**

This file can be used to contain or reference your site JavaScript code.
If you're working on something more advanced you might replace this file
entirely. That's cool. 

**Assets**

This file can be used to contain all your plugins, such as jQuery plugins and
other 3rd party scripts for a simple site.

  **owl.carousel.min**
  This directory can be used to slide contain . 
   
   **oowl.theme.default.min**
  default the  file contains a small script to avoid 
    errors in browsers that lack a  The script will make sure that, if
    a console method isn't available, that method will have the value of empty
    function, thus, preventing the browser from throwing an error.
  

One approach is to put jQuery plugins inside of a `(function($){ ...
})(jQuery);` closure to make sure they're in the jQuery namespace safety
blanket. Read more about [jQuery plugin
authoring](https://learn.jquery.com/plugins/#Getting_Started).

1. First ordered list item
2. Another item
  * Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
  1. Ordered sub-list
4. And another item.  
   
   Some text that should be aligned with the above item.

* Unordered list can use asterisks
- Or minuses
+ Or pluses


<a name="images"/>


## images


The alt attribute provides an alternate text for an image,
HTML File Paths

A file path describes the location of a file in a web site's folder structure.

File paths are used when linking to external files like:
<ol>
<li>Img</li>
<li>index.html</li>
</ol>
 
If a browser cannot find an image, it will display the value of the alt attribute.
    
    
    <div class="listing-item-single">
       <img src="img/destination-2.jpg" class="img-responsive" alt="">
           <div class="listing-overly-content">
             <span class="overlay-like">
             <i class="fa fa-heart-o"></i>340</span>
               <span class="overlay-label">
                     <span class="label-bg3">Building</span>
                    $500/Year
               </span>
                        <span class="item-free">
                          <img src="img/team/t1.jpg" alt="">
                        </span>
           </div>
    </div>
    
<a name="Font"/>
      
## Font


Information about the default JavaScript included in the project.


**Font Awesome**

Font Awesome gives you scalable vector icons that can instantly be 
customized — size, color, drop shadow, and anything that can be done 
with the power of CSS Font face or font family is the typeface that
will be applied by a web browser to some text. The font is relevant 
for the display of text on the screen, on a printer or another device.


    <div class="item">
       <div class="hospitality-single text-center">
          <span>
            <i class="fa fa-trophy"></i>
          </span>
              <h6>Great View</h6>
                <p>Rapidiously optimize multidisciplinary vortals via turnkey practices.</p>
       </div>                                            
    </div>

<a name="HTML-Structure"/>

## HTML Structure


This template use bootstrap framework.For more info please visit this page

             <section class="add-directory-list ptb-100">
                                <div class="add-directory-list-wrap">
                                    <div class="container">
                                        <div class="row">
                                            <div class="col-md-8 col-md-offset-2">
                                                <div class="add-directory-list-content text-center white-text">
                                                    <h2 class="white-text">Post Your Service On Listing Master</h2>
                                                    <p>Phosfluorescently pontificate multimedia based paradigms via premier schemas.
                                                        Energistically conceptualize high-quality outsourcing and interdependent
                                                        e-services.</p>
                                                    <div class="add-listing-btn mt-30">
                                                        <a href="#" class="pxlr-solid-btn"><i class="fa fa-plus"></i> Add
                                                            Listing</a>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </section>
   

### blog.html

Having a lot of content means a lot of scrolling. It helps to make things 
a little easier for your readers if you include an easy way to jump all 
the way back to the top of the page. Adding a Back To Top button can easily
solve scrolling issues and is really simple to implement! I’ve included a really
easy Back To Top button here for you that you can add to any website or blog.
All you need to edit are the theme’s CSS file and the main HTML template file


### blog-details.html

This file contains all settings regarding custom tiles for IE11 and Edge.

For more info on this topic, please refer to

### 404.html

A helpful custom 404 to get you started.

### contact.html

This is the default HTML  contact form is basically a set of questions filled out 
on the webpage by your visitor that is automatically sent to your email when it is
filled out HTML with your setup.

### index.html

Edit this file to include the team that worked on your website and edit code.

### list-details.html

List-details View is a view Overview that displays a list and Video  of scrollable items. The 
list items  Review are automatically inserted to the list using an Adapter that
pulls content from.

### list-list-view.html

List View is a view group that displays a list of scrollable items.

### list-list-view-half.html
List View is a view two item that displays a list of scrollable items. 


<a name="Bootstrap"/>

## Bootstrap

Bootstrap Grid System
Bootstrap's grid system allows up to 12 columns across the page.

If you do not want to use all 12 column individually, you can group the columns together to create wider columns:
Bootstrap's grid system is responsive, and the columns will re-arrange depending on the screen size: On a big 
screen it might look better with the content organized in three columns, but on a small screen it would be better 
if the content items were stacked on top of each other
```no-highlight
  <div class="col-md-4">
    <div class="destination-single panel text-center">
        <img src="img/destination-5.jpg" alt="destination image">
        <div class="panel-body">
          <h3>Maldive</h3>
        <p>Continually expedite progressive</p>
        </div>
    </div>
   </div>                                

```


<a name="Installing"/>


## Installing Template


After unzip the download pack, you'll found a Template Folder with all the files.

You can view this Template in any browser, you can display or edit the Template without an internet connection.

The three sections that will not work is the Google map Section which contains external link to get the map source.

the Contact form which uses PHP, so will work only online.

Now open your FTP Client (like Filezilla) or directly through cpanel, upload the content of the Template on your server root.

Once the files are done uploading go to www.yourdomainname.com/index.html

Please follow the tutorial to have a simple installation of the theme. 


<a name="Reference-link"/>


## Reference link


There are two ways to create links.


[Owl carouse link](https://owlcarousel2.github.io/OwlCarousel2/)

[HTML link](https://www.w3schools.com/html/default.asp)

[bootstraplink](https://getbootstrap.com/docs/3.3/)

Once again, thank you so much for purchasing this templete.
As we said at the beginning, We'd be glad to help you if you have any questions relating to this theme. We I'll do our best to assist. If u have question u can ask us here.

And if u love our theme, pls rate it with 5 stars :D 
Thanks

