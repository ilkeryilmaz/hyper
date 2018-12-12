Hyper
=============

What?
---
Hyper scss to use a CSS framework in frastructure . Its created to new style  move by the common organization of the team work and personal projects can be extended according to the project.

How to use?
---
1. Do Clone / Download then download files by your computer.
2. Carrying the hyper folder to your project , please `@import` main .scss the `hyper.scss` file in your application file.
3. You can start by running your compiler. Happy coding. :sunglasses:


Folder Structure
---
### 1.Settings
Variables , mixins include, functions etc . It is the folder where the properties. The mixins that you can use in your project , sample code for functions and variables are available.

### 2.Tools
Is the folder where the main code of the site. Initially set as the default encoding is located here (normalize, typography, etc.)

### 3.Base
The style files are the main parts of the site is located in this folder.

### 4.Elements
Complementary style of small files are located in this folder.

### 5.Objects
Special style files to pages located in this folder. If desired, create a page for a more sass file folder structure can be created.

### 6.Utilities
Special style files to pages located in this folder. If desired, create a page for a more sass file folder structure can be created.

### 7.Components
Special style files to pages located in this folder. If desired, create a page for a more sass file folder structure can be created.

### 8.Vendors  
Framework and outside the library added style files are located here.

#### hyper.scss
Home sass file. You can `@import` way of typing necessary to your project.

> Can add new files (.scss) to this folders by considering the following description of the structure of your project.


Scaffolding
---
````
hyper/
|
|– settings/
|   |– __all.scss
|   |– _core.scss   
|   |– _theme.scss
|   |– _typography.scss
|   …
|
|– tools/
|   |– __all.scss
|   |– _clearfix.scss    
|   |– _breakpoints.scss
|   |– _fonts-face.scss   
|   |– _rem.scss
|   |– _list.scss
|   |– _grid.scss
|   |– _visibility.scss
|   |– _transition-delay
|   |– _background-retina
|   …                     
|
|– base/
|   |– __all.scss
|   |– _normalize.scss      
|   |– _fonts.scss     
|   |– _typography.scss
|   |– _icons.scss   
|   |– _reboot.scss            
|   …  
|
|– elements/
|   |– __all.scss
|   |– _links.scss      
|   |– _hr.scss             
|   …  
|                   
|– objects/
|   |– __all.scss
|   |– _header.scss
|   |– _main-nav.scss
|   |– _breadcrumbs.scss
|   |– _list.scss
|   …                     
|
|– components/
|   |– __all.scss
|   |– _button.scss     
|   |– _accordion.scss
|   |– _carousel.scss
|   |– _modal.scss
|   |– _slider.scss
|   |– _table.scss
|   |– _box.scss
|   …                   
|
|– utilities/
|   |– __all.scss
|   |– _clearfix.scss 
|   |– _typography.scss 
|   |– _heading.scss 
|   |– _print.scss 
|   |– _visibility.scss 
|   |– _float.scss 
|   |– _gap.scss 
|   |– _responsive-img.scss 
|   |– _scroll.scss 
|   … 
|
|– vendors/
|   |– __all.scss
|   |– _library-file.scss  
|   …                     
|
– hyper.scss  # Hyper Main Scss file
````

## License
MIT license
