# 100 Days Of Code - Log

### Day 0: January 4, 2022 

**Today's Progress**: Checked out some API's where I could get course data from UTM without having to implement my own using a web scraper

**Thoughts:** Looks like VIAplanners API is upto date and is the most verbose option I've seen so far. However, it looks like the API key is only available to primary developers. I also came across an outdated but more open API called Nickel. I'm not sure if Nickel still works but it looks like its available to use currently. It was last updated last year.

**Link(s) to work**
1. [VIAplanner Course API](https://docs.viaplanner.ca/course-api/)
2. [Nickel API](https://docs.nikel.ml/docs)


### Day 1: March 5, 2022

**Today's Progress**: Tried to identify the issue on why I can't access the **grassdata\nc_spm_08_grass7\PERMANENT\windows** folder from withing the simple
python code editor in GRASS GIS. Found out how to list all the accessible rasters from a certain mapset in GRASS.

**Thoughts**: After listing all the accessible rasters from within the PERMANENT mapset using the command ```r_dict = gs.parse_command("g.list", type="rast", mapset="PERMANENT")``` I found that the list of accessible rasters in the PERMANENT mapset were in *grassdata\nc_spm_08_grass7\PERMANENT\cats* while the rural_1m is in *grassdata\nc_spm_08_grass7\PERMANENT\windows*. Have posted a reply on the GIS stack post and am waiting on Damians reply from teams aswell.


**Link(s) to work**
1. [GIS Stack Exchange Post](https://gis.stackexchange.com/questions/425385/cant-access-rasters-from-permanent-mapset-from-python)


### Day 2: May 1, 2022

**Today's Progress**: Followed through a complete Javascript tutorial and made it to the 2 hour mark

**Thoughts**: I've had a brief introduction to the Javascript syntax aswell as common functions, methods and data types. Since I already have a background in programming in another language, understanding how to perform the same operations in Javascript was all I needed to know. I still am missing a proper guide on how to format Javascript code and what rules and traditions I should follow that deem my code as good. I was reintroduced into DOM manipulation and how Javascript, CSS and HTML all work together. I understand how to create divs and style them using flexbox, I still need a better understanding of flexbox and bootstrap. I also learnt the folder structure for a typical website and how every file is in its own folder within the static folder except for index.html which is in the root folder. After this tutorial I can hopefully grind out a tutorial on Javascript operations, syntax and properties on code academy and go through the list of topics I need to understand before I can start React. Hopefully I can get some feedback aswell on how to improve my code and what habits I should start building before I begin React.


**Link(s) to work**
1. [JavaScript Tutorial for Beginners - Full Course in 8 Hours [2020]](https://youtu.be/Qqx_wzMmFeA?t=7828)
2. [How much JavaScript basic is required to jump into a framework like React?](https://www.quora.com/How-much-JavaScript-basic-is-required-to-jump-into-a-framework-like-React)

### Day 3: May 13, 2022

**Today's Progress**: Completed the 4 hour mark for the Javascript tutorial

**Thoughts**: Today I managed to finish the rock, paper, scissors challenge and the button colour changer challenge aswell. I took my time in learning how to do things like grab only all buttons from a certain div and modify its classes appropriately using the right methods instead of just modifying the innerHTML. I posted my rock, paper, scissors problem on code review stack exchange but didn't really get any help except for an edit to my question to I guess make it easier to read. I did get some feedback from reddit regarding the same problem but it focused mainly on obvious things such as declaring two variables in one line and allocating a seperate line for comments, didn't really touch on any Javascript best code practices or anything regarding that nature. I did learn quite alot about some great Javascript coding practices and conventions to make my code less like a "noob" and more like a "pro" from 2 youtube videos. My key take away was probably guard conditions that reduce nested if conditions and improve readability. I do wish I made further progress regarding the youtube tutorial and wish I took notes and maybe practiced solme of the things covered in the best Javascript coding practices so I dont forget, but I might revisit that tomorrow. I also did learn and use more of the forEach method on arrays rather than the typical for loop and learnt that you needed to convert iterable objects like NodeLists and HTMLcollections to arrays for you to utilize the forEach method. I also learnt from the discord server classNames vs classLists and how you can modify classNames easier using strings rather then classLists methods, but also discovered that the value property of classLists is the same as className. I think I did a great job with the button colour changer and even utilized simple one line if conditions. I'm still awaiting feedback on it from someone within the server.

**Link(s) to work**
1. [JavaScript Tutorial for Beginners - Full Course in 8 Hours [2020]](https://youtu.be/Qqx_wzMmFeA?t=7828)
2. [How to get only buttons from a specific div](https://stackoverflow.com/questions/19084509/how-do-you-get-buttons-inside-a-div-only-no-jquery)
3. [Single line if statements](https://stackoverflow.com/questions/8860654/javascript-single-line-if-statement-best-syntax-this-alternative)
4. [For loop for HTMLcollections](https://stackoverflow.com/questions/22754315/for-loop-for-htmlcollection-elements)
5. [Value property in DOMTokenList (classLists)](https://developer.mozilla.org/en-US/docs/Web/API/DOMTokenList/value)
6. [className](https://developer.mozilla.org/en-US/docs/Web/API/Element/className)
7. [forEach method for HTMLcollection](https://www.geeksforgeeks.org/htmlcollection-for-loop/#:~:text=The%20forEach()%20method%20can,an%20array%20and%20display%20them.&text=The%20elements%20can%20be%20iterated,length%20property%20of%20the%20collection.)
8. [Reddit code review on RPS](https://www.reddit.com/r/codereview/comments/up14dx/rock_paper_scissors_game_in_javascript/)
9. [Code Review stack exchange for RPS](https://codereview.stackexchange.com/questions/276508/rock-paper-and-scissors-game)
10. [What forms are in Javasript](https://www.w3schools.com/html/html_forms.asp)
11. [How to loop through 2 lists at the same time with forEach](https://thewebdev.info/2022/03/10/how-to-use-foreach-to-loop-through-two-arrays-at-the-same-time-in-javascript/#:~:text=time%20in%20JavaScript%3F-,To%20use%20forEach%20to%20loop%20through%20two%20arrays%20at%20the,%2C%208%2C%209%5D%3B%20n.)
