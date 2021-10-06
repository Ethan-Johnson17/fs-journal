# Bootstrap
We are using bootstrap v5.1

col-md- is for medium screens
col and then a number (col-9) uses that number of units to determine size of element

Rows can be nested in columns, giving you 12 more units

Don't add left and right margin or padding until you're in a column

You don't have to use all 12 units in a row

Container -> row -> column

Bootstrap link should be linked to html first, and then your style.css

How to get footer to stick to the bottom: body { min-height: 100vh; display:flex; flex-direction: column;}
                                        main {flex-grow: 1;}

Container fluid for heading and footer, goes the full width
container for main, has margins

em unit is better on multiple screen sizes than px

img src="//placehold.it/200x100

class="img-fluid" to to an img to grow and shrink image accoriding to parent element

fonts.google.com -> link font to html under bootstrap and above style.css. Then add it to style.css with font family and style

fontawesome.com or materialdesignicons.com

fa-spin class in bootstrap to spin element

Favorite these on getbootstrap.com:
layout
utilities
components

class="order-md-2" to put the order 2nd on medium screen. Always style mobile first

"d-none d-md-flex" class is good for mobile, you can use it to make big, clunky content disappear on mobile

Imgs can be treated as text -> "text-center"

.card-spill{ transfom: translateY(50px)}

@media only screen and (min-width: 768px){
    .card-spill{ 
        transfom: translateY(50px)
        }
}

bootswatch.com

themestr.app for custom color pallette

Generally best to use one primary color and black and white