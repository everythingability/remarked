# Remarked

This is my attempt at a *markdown-to-html* thingy. I've tried lots of others and they're all OK but they all seem to:

* get quite complicated
* require command-line nonsense
* installing software
* *knacker* your super clean markdown, requiring meta tags and the like
* have a config file so complex that it borders on being a cry for help.


All **Remarked** (I couldn't think of a better name) does is have a super simple index HTML page that uses jQuery to load a markdown file called **Home.md** in the same folder. It uses Blueprint for CSS. CSS in another nightmare hell, but I liked the idea of being able to pretty much just design a super simple single file.

That file is then parsed into HTML using the excellent [marked.js](https://github.com/markedjs/marked), but before that any links are turned into HTML links.

The other thing I wanted to explore was dropping Javascripts that execute into the Markdown files. This would be so that one might have a form (gathering relevant personal details, like name, age, weight etc) page that redirects to this page. The index.html file could then be adapted to ready these values on load, and plop them into variables that I might use throughout the content to display relevant content.

## Installation
Drop the **index.html** into a folder of markdown files, then access it from a server. I'm using my Mac's Webserver folder. Actually that probably won't work now I've added jquery, bootstrap and css files etc), but that's the gist. Download the github repo, and replace the Markdown files with your own, ensuring one is called "Home.md" and then hack the "index.html" to look how you want, and do extra special bits you invent.


## Features?

Surely someone else has done this better? If so, let me know. This has the potential to be hacked to do alsorts of fun stuff, creating "intelligent documents", that maybe know you've read this page, or how long ago you've read it etc. And it isn't a bloody framework or way of life. It's a page of code! (Until you get your hands on it).

Links to [other](Other.md) documents work. Yeah. Let's [do this](Try this.md)?

I wonder if this works with files in [sub-folders](sub-folder/Subfolders.md)?  This is quite nice it means when authoring your markdown files you can just link the regular way, navigating between documents, and it'll work the same in HTML. 

Images work if they're already online or in the same folder.

## What this doesn't do

I think the back button sorta works now.

