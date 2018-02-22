# About this repo
lorem
# Best practises
ipsum
# Image gallery
mah
# Async API Data
dude


# Les 3

## Best practises

Source used: https://www.bizstream.com/blog/december-2016/front-end-best-practices-for-developing-in-kentico

### 01 - FINDING A HOME FOR OUR FILES
Create a safe place to store and host files and make sure you can return easily to older versions and work in branches.

### 02 - ORGANIZED FILE STRUCTURE
css - For our .scss and CSS files.
fonts - For our fonts.
images - For sprites, SVGs, and other iconography. This is not for images added by content admins; those live in the Media Library. 
js - For our JavaScript files. 

### 03 - WRITING BETTER CSS WITH SASS
Sass is more robust, allows you to do more with your code, and is the industry standard pre-processor.

### 04 - CLASS NAMES THAT MAKE SENSE
A semantic class name is one that describes but doesn’t specify the content enclosed. In other words, we want class names that make sense even if the design of the element is changed. For instance, a home page might have a row of three orange boxes. You might think that .orange-box might be a good name, but what if the client wants to change the boxes to blue? Then you’d either have a class .orange-box with a blue background color, which doesn’t make sense, or you’d have to change your HTML to reflect the new .blue-box class name. Better to name it after the purpose of the object: .callout perhaps.


### 05 - GETTING MODULAR

In our code, each module has its own .scss file, where the name of the block class is also the filename. Each project also has the following four.scss files by default:

_mixins.scss - List of Sass mixins.
_normalize.scss - Styles from the latest version of Normalize.
_variables.scss - List of Sass variables and their values.
_global.scss - Global styles, usually site defaults, such as body and paragraph styles.
style.scss - The file that imports in the modules and gets compiled into CSS.


##Zelf

### 06 - Test on slow connections.
Welke content is belangrijkst en moet eerst geladen worden
