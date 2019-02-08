# MassMutual_Web_Page_Assignment

HOW TO RUN:
Create a new folder.
Paste the index.html and css folder inside it.
The index.html is the main html file that you might want to open.  => To see the mobile view , select the mobile icon from the developers tool or resize the browser window.




=====================================================================================================================================
DESCRIPTION:
The css folder has 3 files in it
exercise.css
exercise.css.map
exercise.scss

The exercise.scss file was complied using the command sass --watch exercise.scss which generated the file exercise.css and exercise.css.map  file.
You do not need to do this as the css folder already have these 3 files.

If you need to make any changes in the styling using scss file you need to open the command prompt and navigate to the folder that has exercise.scss and run sass --watch exercise.scss
so that all changes made in scss files are reflected in the css file, as the html file has link to css file.

==========================================================================================================================================
TO MAKE CHANGES TN THE SCSS FILES:

You need to compile the scss file first, for that follow the commands below:

STEPS:
You need to have RUBY installed on your machine
Open command prompt
Navigate to the folder which has exercise.scss
Run the command sass --watch exercise.scss

This will generate two files if you are running the scss file for the first time
exercise.css
exercise.css.map

But if you already have these two files then you will get the following lines on command prompt
Sass is watching fot changes. Press Ctrl-C to stop.
	write exercise.css
	write exercise.css.map
  
Which means that all changes made to excercise.scss are watched and are reflected in the css file.

