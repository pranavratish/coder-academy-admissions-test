# Admissions Test                                        
 
## Why?

Success at coding comes down to many of the elements that contribute to making a person good at anything: hard work, focus, conscientiousness, grit. Working through this content over the next week will hopefully get you excited about what you are about to embark on. 

## Introduction to Test

At any point during this, you may use all of the resources of the internet. We want to see this resourcefulness as you go. If you cannot complete a step, we would like to see what steps you took, some sense of what went wrong, and what error messages were produced.

Better still, read those error messages, and use them to work through the issues you encounter.

If this is all too hard, we would like to see your report on why you struggled. Failure is part of coding. We want to see how you face these challenges, and whether you fight through to the end or not, we would like some record made of the struggle (although should you complete all of the tasks, then this can be brief).

If you can complete the steps, then there's no need to record your progress. But if you get stuck and can't move forward, please note the step you arrived at, what the trouble you had was, what you did to overcome it, and what error messages you found. You could also note the resources you attempted to use to overcome these difficulties (websites, friends, etc). Please send these notes to Elizabeth or Tayla with your final zip file. 

Good luck!

## Test Specs

### Part A

1. These instructions are written with the understanding that you're using MacOS or Linux. If you're using Windows please let Student Services at Coder Academy (Elizabeth or Tayla) know and we'll provide some slightly different instructions.

2. Figure out how to open the program Terminal. This program is also known as the command line. It’s where programmers largely interact with their computers from.

3. There are three commands you now need. One is `ls` which lists the directories (folders) and files in your current location. The second is `cd DIRNAME`, where cd means change directory, and DIRNAME is a stand in for the directory that you wish to change into. The final one is `cd ..` which moves you up one directory in the structure. Use these commands to become familiar with navigating through the filesystem.

4. Now you need one more command, `cd` (or `cd ~`) which will take you to your home directory, no matter where you are in the system. Use this command and then the command `pwd` (print working directory) to see the full path of the location of your home directory.

5. Using the above commands, think about where you would like to make a directory to store your work. You want this to not be far from your home directory (so that you can access it easily) and to have a name that is suitable for your future as a dev.

6. Using your shell, make a directory (or folder) named something suitable for this work. If you’re unsure how to do this google `mkdir command` 

7. Change directory into this newly created directory.

8. Now, from within that directory, create a directory called 'coder-academy-prework'.

### Part B

1. Now we are going to install a program called Git. It helps with version control (so that you may return to a previous version of your software). Even if you think you already have git installed please run through these steps. Follow the instructions outlined by the Git website https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

2. GitHub is a remote repository for your git controlled projects. Sign up to GitHub. https://github.com/

3. Go to this address https://github.com/CoderAcademyEdu/coder-academy-admissions-test

4. In your terminal from the directory where you want to do your work, copy paste the command below, to clone the project you navigated to above.

```txt
git clone https://github.com/CoderAcademyEdu/coder-academy-admissions-test.git
```

5. Now change directory into the project directory.

6. Use the command (hint: it’s one we used earlier) to show a list of the files in this directory. You should see two files, index.html, and style.css.

### Part C

1. Now we need a way to edit those files. Use a browser to go to this page https://code.visualstudio.com/ and follow the instructions to install VSCode.

2. We want to open just the directory we cloned before in VSCode. One way to do this open VSCode then from the menu bar > File > Open > Select the coder-academy-admissions-test directory

3. You should now have an editor window open, and we will make some changes to the files here. Before that, left click on each file to bring them up in the edit window. Have a bit of a look at these files - you will be making changes to them for the rest of the project.

### Part D

1. But first you need to see what you are looking at. Right click or two finger click on MacOS on the index.html file in the left-hand section showing the file system, and then choose 'Copy Path'.

2. Now open a browser and paste the results into the address field of your browser. We'd prefer Chrome to keep things simple. You should now be able to see the webpage that we have made with the code you were looking at before. It's a bit jarring, and we will try to fix this.

### Part E

1. The index.html file contains the basic boilerplate to produce a webpage (everything from `</head>` up), along with the structure that I have added. The style.css file tells that html page what it expects about the specifics of how to render those tags. You will see that the html consists of tags, and that some of those tags have an attribute called class. If you look at the style.css file you'll see that the tag names and the class names (apart from 'div') are represented there. The specific styling rules for each tag are listed between the {} for the class name, and some of them should make some sense just from reading them and looking at the output in the browser. User created classes are added to the tags in the HTML, and are preceded by a dot in the CSS. From here on you will be making some changes, and then checking that these rendered in the browser as you would expect. This will take some getting used to, and some trial and error. You will also need to remember to save your changes in the file, and then refresh the browser page to see the changes.

2. Take careful note of the instructions embedded in the previous step. You will need to refer to them frequently to complete the test.

3. First we will get rid of the rather striking border around the heading. Go into the style.css file and remove the line referring to that border in the h1 section. Now save your file, and refresh the browser. Some relief.

4. The background is still an 'interesting' colour, but we also probably don't need to wish you luck anymore. Lets remove the whole element wishing you luck. Remove the whole line in your html file that contains the words 'Good luck' including the tags (the `<h1></h1>`).

5. In the html file, instead of the title, let's change that you your name. Delete the content from the h2 tags (but not the tags themselves), and insert your name.

6. Let's add to that by having you add a few details about yourself that you are happy to share. Put them into the content of the `<p>` with the class name 'paragraph-one'. It doesn't have to be lengthy.

7. You will notice some other questions on the page. In the tags that come directly below each question (where it says 'Answer 1' and so on) please answer the questions as you see fit. Each time check to see the changes made on the website by saving and then refreshing your browser.

8. You'll notice that some things are hard to read. Let's change that. Let's get rid of the transform line in the .css file. You'll have to find it. Comment it out or delete it.

9. Let's also change the font size for each of the classes that start with 'paragraph'. Change each of the font-size attributes to read 2rem.

10. Then get rid of any other styling in those classes (you can just delete it).

11. We don't have an h1 anymore, so we can remove the styling for the h1 altogether (although that will not change the styling).

12. Change the h2 font-size to 4rem, and the h3 font-size to 3rem.

13. Delete the redundant rule for the paragraph three class (there are two of them now, and both say the same thing).

14. Add a class called paragraph four that matches paragraph three. You can copy and past and make the appropriate changes.

15. You'll notice that some of the text is still aligned right. We will get rid of that. It is being passed down through the div that has the class 'our-div'. Change the attribute so that instead of aligning right it now aligns left.

16. Let's release the text a little. Find and change the value of the max-width attribute from 30rem to 45rem.

17. Now we want to see about changing our fonts. You'll have plenty of chances to investigate this when you start, but today you'll just follow instructions. Go to this website, and have a browse https://fonts.google.com/

18. In the search field type 'cormorant' and press enter.

19. It should bring up six variants within this font family. Click the plus next to the one called 'Cormorant Garamond'. Down the bottom of the screen a black bar with '1 Family Selected' will appear. Click it.

20. In that popped window you will see a section of text that starts with `<link href=...>` which you should highlight and copy.

21. Paste it directly beneath the code that is very similar in the head of your HTML file.

22. Return to the window that contains the instructions for loading the font (where you recently copied from). Here you will see an instruction of how to copy this font into your CSS file. Copy the relevant text.

23. Paste that text into each of the classes that have a name containing 'paragraph' (eg. `.paragraph-one`).

24. Change the background colour to silver.

25. And the colour of the font (which is the 'color' attribute) to `midnightblue`. It looks marginally better than when we started!

### Part F

1. And you are done! Now we need you to zip up your project (with the style.css and index.html files inside, and any notes document you may have needed to make), and send the zipped folder to Tayla or Elizabeth! Well done!

## Things to Note

Coding at home is hard. If you get stuck at any point and a quick google search is not helping you out, please don’t hesitate to make contact and get a nudge in the right direction.

Email: elizabeth.lee-finkelstein@coderacademy.edu.au
Email: tayla.turcinovic@coderacademy.edu.au 
