Hyper
=============
[![Build Status](https://travis-ci.org/ilkeryilmaz/hyper.svg)](https://travis-ci.org/ilkeryilmaz/hyper)

<p align="center">
  <img src="docs/assets/hyper.svg" alt="logo" />
</p>

Hyper: A component-first CSS design system. 


Folder Detail
---

* `1. settings`: Global variables, theme confing and typography settings, etc.
* `2. base`: Low-specificity, far-reaching rulesets (e.g. normalize, typography, fonts).
* `3. tools`: The style files are the main parts of the site is located in this folder.
* `4. elements`: Unclassed HTML elements. (eg. `a { }`, `hr { }`,)
* `5. objects`: Objects, abstractions, and design patterns (e.g. `.o-layout {}`).
* `6. components`: Discrete, complete chunks of UI (e.g. `.c-carousel {}`).
* `7. utilities`: High-specificity, very explicit selectors. Overrides and helper classes (e.g. `.u-hidden {}`).
* `8. vendors`: Outside library files. (e.g magnific-popup, jquery-ui, )

> `hyper.scss`: Home sass file. You can `@import` way of typing necessary to your project.

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
– hyper.scss  # Hyper main scss file
````

## License
MIT license
