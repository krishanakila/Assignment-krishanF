# Assignment-krishanF

This project was generated with Angular CLI version 10.1.1.

# My PC Version

$ node -v
v12.14.1

$ npm -v
6.13.4

# To Run The Project

1) npm i
2) ng serve

Development server
Run ng serve for a dev server. Navigate to http://localhost:4200/. The app will automatically reload if you change any of the source files.

# Adobe XD link - Prototype 

https://xd.adobe.com/view/44891c9b-6ab5-4702-9400-f20096ce946d-11da/

# Best practices used for this project.

Scss File Architecture Structure (ITCSS)


A curated list of awesome ITCSS articles, and resources.

sass/
|
|– theme-settings/
|   |– _color.scss       # Theme colors
|   |– _brand.scss       # Brand logo
|   |– _font.scss        # Theme fonts
|   |– _icon.scss        # Icons
|   ...                  # Etc…
|
|– tools/
|   |– functions/        # Sass Functions
|   |– mixins/           # Sass Mixins
|   ...                  # Etc…
|
|– generic/
|   |– _normalize.scss   # Normalize
|   |– _reset.scss       # Reset
|   |– _base.scss        # Base rules
|
|– objects/
|   |– atoms/            # Atoms
|   |– molecules/        # Molecules
|   |– organism/         # Organism
|
|– layouts/
|   |– _grid.scss        # Grid
|   ...                  # Etc…
|
|– components/
|   |– _sample.scss      # Grid
|   ...                  # Etc…
|
|– pages/
|   |– _home.scss        # Home specific styles
|   |– _contact.scss     # Contact specific styles
|   ...                  # Etc…
|
|– utilities/
|   |– _clearfix.scss    # Clearfix
|   |– _helpers.scss     # Class & placeholders helpers
|
|
`– styles.scss            # Primary Sass file
