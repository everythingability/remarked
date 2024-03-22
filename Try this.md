# Try this


Here is some code displayed, but hopefully I can execute javascript code as well.

Although you can't see it, there is some javascript in this page, that does a calculation then puts a value into a div called "answer". It's not the most elegant way to do this perhaps, it is the simplest.

I could think about parsing my own script tag, and then eval() the code or something, but that way I would inevitably end up creating "a language" or some such.  I don't have the brains. 

```js
// x is defined in the index.html as being 100.
// This might be useful if used in combination with a form etc
//  

var y = 10


```

<span id="answer"></div>

<script>
//
var y = 10
var answer = x + y

document.getElementById("answer").innerHTML = "x + y = " + answer


</script>

Can I do [Creation going forward](Creation going forward.md)?