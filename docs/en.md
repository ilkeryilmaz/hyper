What?
---
Hyper sass to use a CSS framework in frastructure . Its created to new style  move by the common organization of the team work and personal projects can be extended according to the project .


How to use?
---
1. Do Clone / Download then download files by your computer.
2. Carrying the hyper folder to your project , please `@import` main .scss the `hyper.scss` file in your application file.
3. You can start by running your compiler. Happy coding. :sunglasses:

Folder Structure Details
---
1. [Helpers](#helpers)
2. [Base](#base)
3. [Layout](#layout)
4. [Components](#components)
5. [Pages](#pages)
6. [Vendors](#vendors)

> Can add new files (.scss) to this folders by considering the following description of the structure of your project.


## Helpers
Variables , mixins include, functions etc . It is the folder where the properties. The mixins that you can use in your project , sample code for functions and variables are available.

### File List
* _variables.scss (Sass Variables)
* _function.scss (Sassi Functions)
* _mixin.scss (Sass Mixins)

## Base
Is the folder where the main code of the site. Initially set as the default encoding is located here (normalize, typography, etc.)

### File List
* _normalize.scss
* _animations.scss
* _typography.scss
* _print.scss
* _base.scss

## Layout
The style files are the main parts of the site is located in this folder.

### File List
* _header.scss
* _nav.scss
* _breadcrumbs.scss
* _sidebar.scss
* _footer.scss

## Components
Complementary style of small files are located in this folder.

### File List
* _accordion.scss
* _carousel.scss
* _alert.scss
* _button.scss
* _label.scss
* _slider.scss
* _table.scss
* _modal.scss
* _tab.scss
* _video.scss

## Pages
Special style files to pages located in this folder. If desired, create a page for a more sass file folder structure can be created.

### File List
* _home.scss
* _contact.scss
* folder / _all -> Example folder structure

## Vendors  
Framework and outside the library added style files are located here.

### File List
* _bx-slider.scss
* _jquery-ui.scss

### hyper.scss
Home sass file. You can `@import` way of typing necessary to your project.
