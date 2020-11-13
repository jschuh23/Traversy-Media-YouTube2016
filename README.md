# Traversy-Media-YouTube2016
Traversy Media - YouTube 2016 Project "Build An HTML5 Website With A Responsive Layout"

This project followed the design presented in the YouTube video (https://www.youtube.com/watch?v=Wm6CUkswsNw&t=313s), but I adjusted some portions to fit more inline with the current techniques I've learned.

MY ADJUSTMENTS
1. Mobile-first design with media queries set at:
    - min-width:500px
    - min-width:768px
    - min-width:1280px

2. Utilized Sass and created a 7-1 folder structure containing the following folders and files:
    - abstracts
        _variables.scss
        _functions.scss
    - base
        _reset.scss
        _typography.scss
        _utilities.scss
    - components
        _buttons.scss
    - layout
        _navigation.scss
        _forms.scss
        _responsive.scss
    - pages
        _home.scss
        _about.scss
        _services.scss

3. Utilized the BEM (Block Element Modifier) methodology for my naming convention in HTML and CSS

4. Adjusted color scheme to meet the WCAG 2 AA contrast ratio thresholds

5. Used Grid and Flexbox for layouts

6. Used the clamp() CSS function for certain font-sizes to make them more responsive
