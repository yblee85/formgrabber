varformgrabber

it doesn't need to be insdie <form>
it read elements from html and creates json object

example.

-- html --<br>
input element: input type="text" var="txtName"

-- js --<br>
var data = varFromGrabber($("#divHere"));<br>
// data = {txtName : "..."}

