![GeneralAssemb.ly](../../img/html-css.png)

# Welcome to Intro to HTML and CSS!

---

## Agenda

* Introduction
* Sublime Text
*	HTML Tag Review
*	GA Press Release Codealong
*	Lab Time

---

## Introduction to Front End Web Development

--

## What is Web Development?

--

## What is Web Development?

* The practice of creating applications and experiences that users interact with via the World Wide Web.
* Most often, the act of turning ideas and design compositions into a real, usable website.
Made up of many smaller disciplines: front end development and back end development.

--

## What do front-end developers do?

--
## Client-Side Development

The client is the application the end-user runs to use your website. In most cases, a web browser such as Chrome or Firefox.

Languages include:

* HTML
* CSS
* Javascript

Note:
Front-end is all about keeping the 'everywhere' in mind, and making the best
experience possible in every context.

--

## What do back end developers do?

--

## Server-Side Development

The server is the thing that handles the requests coming from your client. Back-end code runs only on the server, and responds in languages the client understands.

Languages include:

* Ruby
* PHP
* Python
* Node.js

Note:
Every web page meant for public use needs a server, but that doesn't necessarily mean server-side coding.

---

## Coding Environment

What do our computers and a web server have in common?

--

**A URL**

![A url](../img/unit_1/server-path.png)

--
**A finder window**

![A finder window](../img/unit_1/file-path.png)

--

**OMG! They're the same!**

![OMG they're the same](../img/unit_1/file-path2.png)

--

** Without a backend, the Web is just files in folders on a computer somewhere.**

Note:
Let's be that somewhere!

--

We're going to create a folder called **FEWD** on your desktop, and keep all of our course work there.

--

In FEWD, add a folder called **class01**. We'll create folders in here for our coding exercises today. You can think of each folder that pertains to a specific exercise or lab as its own website. Essentially, that's what it is.

--

All of the files (HTML files, images, stylesheets, etc.) that are related to a given website should go in that site's folder, not someplace else on your computer.

```/img``` folder

```/css``` folder (this will be empty for now)

```/js``` folder (this will be empty for now)
--

Go to folder (in your mac's finder)

**cmd+shift+G**

--

**~** is your 'home folder'  
**~/Desktop** is your desktop,  
**~/Documents** is your documents folder, etc.

--

Start typing and hit **tab** to autocomplete!
![Tab completion in finder](../img/unit_1/tab_completion.png)

---


##Sublime

![Sublime](../img/icons/sublime.png)

--

Sublime is *fantastic* and has an unlimited free trial

http://www.sublimetext.com/3

Open the .dmg file and drag the icon to your applications folder.
Windows: Run installer

--

## Opening Files in Your Browser

1.  Make a folder called `hello`. Drag `hello` onto the Sublime Text icon in your dock to open it.
1.  Right-click on `hello` in the sidebar, select `New File...`.
1.  Call it index.html (Look at the bottom of the app for the text field where you name the file).
1.  Open the file and type `<h1>hello, world!</h1>`
1.  Save the file. (`cmd+s` on mac, `ctrl+s` on windows/linux)
1.  Right-click `index.html` in the Sublime sidebar and choose `Open In Browser`.

---

##HTML Basics

---

##HTML vs HTML5

HTML5 is HTML with a few additions
The Doctype tells you if the page is HTML5 ready.


```<!DOCTYPE html>```


![HTML History](../img/unit_1/Timeline_of_web_technologies.jpg)

Note:
image retrieved from http://www.onbile.com/info/wp-content/uploads/2013/09/Timeline-of-web-technologies-639x168.jpg on October 1, 2013.
--

##HTML HISTORY

[![Website History](../img/unit_1/History-of-Website-Development-Infographic_0.png)](https://pantheon.io/sites/default/files/History-of-Website-Development-Infographic_0.png)
Note:
image retrieved from https://pantheon.io/sites/default/files/History-of-Website-Development-Infographic_0.png on March 21, 2015.

---

##HTML Syntax

![HTML Syntax](../img/unit_1/tags.png)

---

##HTML Syntax

![HTML Syntax](../img/unit_1/tags_attributes.png)

---

![GeneralAssemb.ly](../img/icons/code_along.png)
##General Assembly Press Release

---

##HTML Page Structure


```<!DOCTYPE html>```

```<html>``` ``` ```

```<head>``` ```</head>```

```<body>``` ```</body>```

```</html>```

--

##Semantic Page Tags


```<header>``` ```</header>```

```<article>``` ```</article>```

```<footer>``` ```</footer>```

---

##Content Tags

###Heading Elements

```<h1>```Largest Heading```</h1>```

```<h2>``` . . . ```</h2>```

```<h3>``` . . . ```</h3>```

```<h4>``` . . .```</h4>```

```<h5>``` . . . ```</h5>```

```<h6>```Smallest Heading```</h6>```

--

##Content Tags

###Text Elements

```<p>```This is a paragraph```</p>```

```<span>```This text is inline```</span>```

```<code>```This is some computer code```</code>```

--

##Content Tags

###Unordered list

```
<ul>
  <li>First item</li>
  <li>Next item</li>
</ul>
```

--

##Content Tags

###links

 ```<a href="Link">```First item```</a>```

---

![GeneralAssemb.ly](../img/icons/exercise_icon_md.png)
##Cookie Recipe

---

## Homework

* Watch [this video](https://www.youtube.com/watch?v=7_LPdttKXPc) about the Internet.
* [HTML Cheat Sheet PDF](../pdf/html-cheat-sheet-v1.pdf)
* Read about CSS Colors