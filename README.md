# Admissions Test                                        
 
### GitHub link

https://github.com/pranavratish/coder-academy-admissions-test

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
