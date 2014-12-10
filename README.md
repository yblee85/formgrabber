varformgrabber

it doesn't need to be insdie <form>
it read elements from html and creates json object

example.

-- html --
"<div id=\"divHere\">
<input type=\"text\" var=\"txtName\"></input>
</div>"

-- js --<br>
var data = varFromGrabber($("#divHere"));<br>
// data = {txtName : "..."}

