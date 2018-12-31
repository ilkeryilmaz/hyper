Hyper
=============
[![Build Status](https://travis-ci.org/ilkeryilmaz/Hyper.svg?branch=feature%2Fnew-version)](https://travis-ci.org/ilkeryilmaz/Hyper)

<p align="center">
  <img src="docs/assets/hyper.svg" alt="logo" />
</p>

Hyper: A component-first CSS design system. 


Folder Structure
---
### 1.Settings
Global variables, theme confing and typography settings, etc.

### 2.Base
Low-specificity, far-reaching rulesets (e.g. normalize, typography, fonts).

### 3.Tools
The style files are the main parts of the site is located in this folder.

### 4.Elements
Unclassed HTML elements. (eg. `a { }`, `hr { }`,)

### 5.Objects
Objects, abstractions, and design patterns (e.g. `.o-layout {}`).


### 6.Components
Discrete, complete chunks of UI (e.g. `.c-carousel {}`).

### 7.Utilities
High-specificity, very explicit selectors. Overrides and helper classes (e.g. `.u-hidden {}`).

### 8.Vendors  
Outside library files. (e.g magnific-popup, jquery-ui, )

#### hyper.scss
Home sass file. You can `@import` way of typing necessary to your project.

> Depending on the structure of your project, you can add new scss files to expand the structure. You're free.


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
