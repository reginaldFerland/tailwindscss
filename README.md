# tailwindscss
A SCSS remake of tailwindcss

## Build css from scss
You can build the css file to import with the sass command line tool.
Simply run the following command and the file will be put into the dist folder:
sass src/index.scss dist/index.css

## Classes being skipped / deprioritized
* Background image classes, need to investigate design approach
* Background gradent classes, need to investigate design approach
* Content class, need to determine the configuration approach
* Ring Width / Ring color / Ring offset width / ring offset color, need to determine css variable management approach

## TODO:
* pick a minimizer
* pick a tree shaker
* refactor color variations
* add state variations
* add methods to extend size & color options
