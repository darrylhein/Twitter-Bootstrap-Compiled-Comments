Twitter Bootstrap CSS
=====================

This is just the compiled, formatted and commented code from [Twitter Bootstap](http://twitter.github.com/bootstrap/). We have no rights to the code and are not responsible for any problems. Please contact them with questions. See their page for documention.

The source directory contains the compiled files from the lib directory in the Twitter Bootstrap. They have been compiled together and then separated out, allowing you to only include the CSS you need.

To create the bootsrap.css file, run the following command from whereever you have stored all of the separated CSS files:

 `cat reset.css scaffolding.css type.css forms.css tables.css patterns.css > bootstrap.css`
 
 This will create a CSS file with all of the files combined. If you don't need one of the files, simply remove it from the list. We recommend keeping reset.css and scaffolding.css at a minimum, although type.css is extremely useful as well.
 
 We have kept a lot of the CSS on the same line as the selector as we find it easier to read and reduces the number of lines you need to scroll through.
 
 We recommend minifying the CSS before using it on production to remove comments and extra spaces. This will reduce the size considerably.