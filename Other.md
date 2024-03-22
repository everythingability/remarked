# I am an other markdown file

* Isn't this lovely?
* Isn't this wonderful?
* Isn't this simple?
* Isn't this like, a page of code?

I have to have a link [somewhere else](YesIDo.md)

![](cow_PNG50627.png)

This is more text And below is some javascript that executes...when it's a web page, obviously it doesn't show when I am editing the markdown file.

<script>

// Do scripts work?
$('#content').append($( "<h1>Moo!</h1>" )) //Yes!!
$('#content').append($( "<p>That moo was scripted to be there</p>" )) //Yes!!

// can I add javascript vars, so I might respond to a person
// and show different content?
$('#content').append($( `<p>${x}</p>` )) // Yes!
$('#content').append($( `<p>That number (100) is a javascript variable</p>` )) // Yes!

</script>

This is what editing this page looks like.

![Editing with Markdown app](editing_with_markdown.png)