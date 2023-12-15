------------------------------------------------------------------------------------------------------
# [Moz-Dev](https://developer.mozilla.org/en-US/) - refer for all developers about web related content 
------------------------------------------------------------------------------------------------------

## **Prerequisites**

Browser - Chrome , firefox , edge , Brave , safari[iOS]
Vs code - Html css extension - Live Server extension

------------------------------------------------------------------------------------------------------
## **Lession 01**
------------------------------------------------------------------------------------------------------

`! in vs code for html predefined structure to show`

### Types of Styling: 
- inline
- internal
- External

Style Applies on order of precedence
The !important css over rides all the order of precedence.
You should use only one !important.

link rel="stylesheet" => import the file as stylesheet
link rel="canonical" =>
link rel="author" => 

### css code syntax:
selector (class,id,tag) {
property (font-size, display , position) : property-value (50px , 10rem , 100% , red , #kvnk) ;
}

Css validator W3C -> [Css validate](https://jigsaw.w3.org/css-validator/) 

------------------------------------------------------------------------------------------------------
## **Lession 02**
------------------------------------------------------------------------------------------------------

### Selectors
class - .demo
id - #name
tag - p div span
body , html , * - universal or document level declaration 
group selector with a comma between individual selectors - div, span {}
parent child selectors - div span{} 

Css Selector works as it acronym cascading like a waterfall [top to down]

inherit property >> body it only applies to the body tag , whereas * applies to all elements like span p div h2 h3 ....
form element don't inherit the body/html property like font, border , margin , padding.

main element/selector = 1 per page = semantic tag 

**specificity css works**
id selector >> class selector >> element selector


------------------------------------------------------------------------------------------------------
## **Lession 03**
------------------------------------------------------------------------------------------------------

### Colors
140 standard color names available in [html/vscode](https://www.w3schools.com/colors/colors_names.asp) 

**Types of color css**
- Color name = orange blue
- hexadecimal code = #fff000 [0-9] + [a-f]
- rgb (200, 255 , 0) = [0-255] [0-100%]
- rgba (200. 255 , 0 , .5) = opacity [0 to 1 , decimal value accepted]
- Color pallete selection with hovering over css color properties with opacity
- hsl (200, 255 , 0) = [0-255] [0-100%] = hue saturation lightness

https://coolors.co/ - colors contrast trending vectors checking


------------------------------------------------------------------------------------------------------
## **Lession 04**
------------------------------------------------------------------------------------------------------
