sassy_s
=======

... is the Underscores base stylesheet refactored as scss partials.

(Underscores, if you don't know it, is a completely awesome starter theme for WordPress.)

Prerequisites
-------------

You will need to have Sass installed, if you don't already have it. (If you're new to Sass, start here: http://sass-lang.com/tutorial.html and here: http://www.alistapart.com/articles/getting-started-with-sass/)

You'll also need a fresh copy of Underscores for each new project. I strongly recommend using http://underscores.me to set up a customized copy for your project.

Now, clone me.
--------------

1. Drop the entire sassy_s folder into your theme folder.

2. *Before you start editing*, copy the header from your customized Underscores style.css to sassy_s/style.scss

3. From the command line:

	    cd path/to/your/theme
	    sass --watch sassy_s/style.scss:style.css

	(Or use your preferred Sass GUI to set your input to the sassy_s directory and your output to the main stylesheet.)

4. sassy_s comes with a few examples of variables and mixins to get you started.