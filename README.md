# Simple_Static_Starter---HTML_SCSS_JavaSript

 A simple starter for creating static websites. Uses the Sass(scss) preprocessor, integrated horizontal menu (with the ability to rewind the scroll to the desired section)

 Link GitHub page (Live demo) https://danmiles.github.io/Simple_Static_Starter---HTML_SCSS_JavaSript/

1) Bootstrap 5 is taken as the basis, only the grid is used. I also use the Sass preprocessor to work with CSS. If you want all bootstrap 5 functionality you can uncomment the line inside <head> and also at the bottom of Index.html

2) But the main layout only uses the bootstrap grid to speed things up, since I don't need all the functionality of bootstrap 5.

3) The most basic feature is the menu, which you can easily customize (colors) using the _variables.scss file.
The menu can scroll to the desired section, the structure is shown in index.html

4) To compile Sass to Css I use prepros.io. But you can use any other technologies (visual studio code or gulp.js extensions).
I also use a media query mixin (scss folder), you can see how to use it in the main.scss example

5) The boxicon and bootstrap 5 icons are in the plugins folder.

6) If you install fonts locally (there is a special mixin file _fonts.scss)
