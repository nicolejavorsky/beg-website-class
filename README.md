# HTML / CSS Curriculum for Harlem Grown's Summer Camp
Harlem Grown's mission is to inspire youth to live healthy and ambitious lives through mentorship and hands-on education in urban farming, sustainability, and nutrition.
I am teaching a HTML / CSS class twice a week for the duration of the camp that is themed around food sustainability and environmental justice.
# Table of Contents
1. [Timeline](#timeline)
2. [Week1](#week1)
3. [Week2](#week2)
4. [Week3](#week3)
5. [Week4](#week4)

## Timeline
| Week        | Monday           | Wednesday  |
| :-------------: |:-------------:| :-----:|
| 1      | Food Production | Intro to HTML |
| 2      | Make web page about food production      |   Intro to CSS, Spice up web page with CSS |
| 3 | Sustainability      |    Review HTML / CSS concepts |
| 4 | Environmental Justice      |    Menu/File Structure, Make website about children’s stories |
| 5 | Finish stories website      |    Introduce final project |
| 6 | Workday      |    Workday |
| 7 | Presentations      |    Presentations / Celebration! |

## Week1
**Monday**
* Lesson
	1. Show the kids two tomatoes (one purchased from a typical supermarket, one from Harlem Grown farm)
	2. Explain that these two tomatoes have different cycles of food production
	3.  Go through tomato 1 and 2 (general description) 
* Activity
	1. Divide the kids into two groups and assign each group one tomato
	2. Ask them to draw the food production process for the tomato
	3. What do the seeds look like? What does the farm look like? Who is working on the farm? What happens after harvest? Who is buying or eating the tomato?

**Wednesday**
* Introduction to HTML
  1. So, what does HTML stand for? HyperText Markup Language! You're probably thinking, "I still have no idea what this HTML thing is." I don't blame you! Basically, HTML allows us to create content for websites. This can include things like inserting images, tables, headings, paragraphs of text, and more.
  2. I hate to break to you, but using HTML alone ain't pretty. If you've seen any websites yourself, you have probably noticed colors, font-sizes, and other wonderful styling. This does NOT come from an HTML document. Think of HTML as the skeleton of your website and there's something else to transform that. In other words, we need something to make that skeleton into a living, breathing human instead of an ugly structure of bones. Sorry for the creepy image I may have just given your mind!
  3. Okay, so what is that something? How does the skeleton become a person? How do we make the plain website look good? With CSS! Ah, another set of letters with no obvious meaning. Yeah, CSS means Cascading Style Sheets. Yup. Basically, CSS gives the skeleton webpage life with colors, fonts, and other styling.
  4. Now, you have an idea of how websites come together. There's an HTML document for structure and there's a CSS document for styling.
  5. Yeah! Go us! Can someone explain all of this stuff? Put it in your own words. One volunteer and then we'll start our first HTML document!
  ```html
  <!DOCTYPE html>
  <html> 
	<head>
	   <title>My Website</title>
	</head>
	<body>
	   <h1>Hi I am Nicole!!!</h1>
	   <p>Harlem Grown rocks!</p>		
	</body> 
  </html>
  ```
## Week2
**Monday**
* Introduce Project #1: Make web page about food production. Include photo of mural made during Week 1 in webpage.  (Use this as an opportunity to teach about including images in websites.)
  1. How will you be able to include the image of the mural in your website?
  ```html
  <img src="mural.jpg">
  ```
  Let's break it down. The "src" shows the source a.k.a "WHERE IS THE IMAGE COMING FROM???" Inside the quotation marks, we have the filename of the image. Be careful though. If you put your images in a folder, you have to let the internet know where to look for your file!
  For example, if your image mural.jpg is inside a folder called images, you gotta say that! Here's how that works:
  ```html
  <img src="images/mural.jpg">
  ```
  Pretty simple, right? Well, we will have to make this a bit more complicated. I promise that you can do it though! So, on Wednesday, we will learn about how to make the web page prettier and how to make this image fit better on page.
  
**Wednesday**
* Introduction to CSS
  1. Let's review. What does CSS stand for? CSS stands for Cascading Style Sheets. What does it do? Spices up your website!
  2. Okay, let's go over some things you can do with CSS:
  * ADD!
  3. Now it's time to create a CSS file to go with your HTML file from last time.
  4. Pull up your HTML file in your browser.
  5. WAIT. NO. WHY ISN'T THIS WORKING?!
  6. You need to link the two files together. Right now, the HTML and CSS files are sitting side by side in your folder. However, your HTML file doesn't know that. So, let's try this:
  ```html
  <link rel="stylesheet" type="text/css" href="1.css">
  ```
  Let's break it down. First, you're saying, "Okay, I'm linking to a style sheet." Then, "Yeah, the type is a CSS text file." Finally, you're saying, "Here's the filename so you can find what I'm talking about." Kinda similar to adding images, right? Tell me how.

## Week3
**Monday**
* Lesson
	1. What is sustainability? Quick brainstorm
	2. Explain what it is & key words associated with it (mindful, long-term, future generations, resiliat, self-reliant)
* Activity
	1. Designing a resilient community (what does your community look like)? 
	2. What happens to the community when there is a fire? flood? No jobs? Theft?
	3. Choose one volunteer and ask them to pick from a list of products
	4. Explore the connections to the outside world, and how this item has an ecological footprint, what systems its a part of, and how sustainable it is. 

**Wednesday**
* Review of HTML / CSS
  1. Take questions. Go over past things learned. If the kids want to learn more, delve further.

## Week 4
**Monday**
* What is environmental justice? Have the kids throw out their ideas and write it on chart paper.
* Have the kids write down a story about an experience they've had around the concept of environmental justice.
* Human Barometer Activity
  1. ADD QUESTIONS HERE! 
