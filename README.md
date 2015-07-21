**This project is not maintained anymore.**

# Blankplate

## Yet another HTML5/CSS3 Starter Kit
This is an alternative solution to save you time in frontend developing.

[Check out the demo][1]

## How this will help you

This package provides you with all you need to start building your web page quickly, still keeping an organized structure and a consistently stylesheet.

In short, this package contains a batch of reset and basic css rules, useful helpers etc; anything but annoying rules for grids or with strange paddings and margins.

## A quick and dirty example

Need three navigation menus one horizontal for your global menu, one vertical for your side section and another horizontal in the footer section.
You do not have to create extra rules and mess with display or float properties, just apply
`.horizontal` or `.vertical` class to your ul element and that’s it, now you are free to append your actual "styling" properties.

## What it does

It resets and redefines in a more rational way your html elements, offers you a collection of helpers, informs you on empty html elements and atributes, provides you with a basic folder/file/coding structure.

## What it doesn't

It does not interfere with your design, basically there are not predefine colors, paddings, margings or other dimensions. Consider Blankplate as a chassis for your project.

## The package

Directory structure:

    fonts/                          <!-- dummy fonts to use with @font-face-->
        dummyfont.eot
        dummyfont.otf
        dummyfont.svg
        dummyfont.ttf
        dummyfont.woff
    images/                         <!-- for your images with a dummy image-->
        dummy.png
    js/                             <!-- for your js files with a minified jquery 1.8.1-->
        ga.js                       <!-- google analytics tracking code-->
        initializers.js             <!-- initializers for your js scripts-->
        plugins.js                  <!-- your custom js scripts-->
        vendor/
            css3-mediaqueries.js
            selectivizr-min.js
            jquery-1.8.3.min.js
            jquery.placeholder.min.js
    styles/                         <!-- styles folder-->
        base64.css                  <!-- base64 encoded pngs-->
        buttons.css                 <!-- buttons and colors-->
        diagnostics.css             <!-- css diagnostics-->
        helpers.css                 <!-- helpers-->
        inputs.css                  <!-- basic rules for inputs-->
        media.css                   <!-- media queries-->
        reset.css                   <!-- a good reset-->
        snippets.css                <!-- useful snippets of css and html code-->
        styles.css                  <!-- almost empty to put your main rules-->
        typography.css              <!-- typography rules-->
    index.html                      <!-- basic HTML5 structure-->
    demo.html                       <!-- a demo page-->
    LICENCE.txt                     <!-- licence-->
    README.md                       <!-- readme - this file-->
    TODO.txt                        <!-- next steps-->

## Browser support

 - Chrome 1+
 - Firefox 3+
 - Internet Explorer 7+ *
 - Opera 10+
 - Safari 4+

## Demostration

A demo page is available [here][1].

## Credits

Thanks to [Vassilis Rodokanakis][3] blankplate can be integrated through [blankplate-rails][4] gem with Rails Asset Pipeline!

## Copyright and license

Copyright 2012 Dimitris Krestos

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0][5]

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

  [1]: https://dl.dropbox.com/u/28039153/blankplate/demo.html
  [2]: https://dl.dropbox.com/u/28039153/blankplate/LICENSE.txt
  [3]: https://github.com/vrodokanakis
  [4]: https://github.com/vrodokanakis/blankplate-rails
  [5]: http://www.apache.org/licenses/LICENSE-2.0