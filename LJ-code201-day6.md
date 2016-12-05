# Notes for 12/5/16

Todays lab is solving a problem domain by identifying its particular objects and methods.

-have one job done by one method only (try to keep it to less than 15 lines of code per single method or function)

-use the THIS variable within methods so you cans a access the objets properties and methods from inside.

## DOCUMENT OBJECT MODEL aka THE DOM

example sight:

<html>
	<head></head>
	<body>
		<h1> My TAs </h1>
		<ul>
			<li>R</li>
			<li>A</li>
			<li>Ken</li>
			<li>Kevia</li>
		</ul>
	</body>
</html>

### The same Javascript can be used to affect multiple documents
document.body can be used to make a new element in html, and then assign it content, as well as specifying where it goes in the document

every online document is going to have an html head and body, therefore allowing those to be manipulated by the developers

how to make an element in JS:
var h1El = document.createE
undefined
var h1El = document.createElement('h1');
undefined
h1El
<!== this is what h1E1 is defined as now >:  <h1>​</h1>​

How to apply to actual HTML
h1El.textContent = 'My TAs';
"My TAs"
h1El
<h1>​My TAs​</h1>​
document.body.appendChild(h1El);
<h1>​My TAs​</h1>​
Create the Element

var h1El = document.createElement('h1');
-this creates a a document element
h1El
<!== this is what h1E1 is defined as now >:  <h1>​</h1>

Give it content
h1El.textContent = 'My TAs';
"My TAs"
h1El
<h1>​My TAs​</h1>​

Append element
document.body.appendChild(h1El);
<h1>​My TAs​</h1>​

-USE HTML to write structure, USE JAVASCRIPT to create repeating elements

##Objects vs Arrays

Array elements are always associated with each other whereas objects may have multiple objects properties(just informations) or method (a method is a function that is attached to an object)

examples:  frazier is the object property, Fraz is the object property value
var emptyObject = {};
emptyObject.frazier = ‘Fraz’;

Example of an object Literal:

var genericObject = {
  key1: 'value1',
  key2: 'value2',
  'multi-word key': 'value3',
  method: function() {
    //do stuff
    alert('YOU DONE CALLED MY METHOD ERMAGEHRD');
  }
};

## How to do functions within objets aka METHODS
var listYourObjectName, assignment operator, {do stuff};






ObjectLiteral for today’s Calculate daily sales projections (sales.html) lab:

var alki = {
      minCustPerHour: 5,
      maxCustPerHour 7,
      avgCookiesPerCust: 15,
 // need method HERE
      randCustPerHour: function() {
	magic
      },
      cookiesSoldEachHour: [],
      calcCookiesSoldEachHour: function () {
	for over this.randCustPerHour {
	      this.randCustPerHour
	}
      }
};

also use the logic sumArray to do part 6 of sales.html

for () {
      this.cookiesSoldEachHour.push(maths);
      }

###HTML output for our LAB

<body>
	Alki
	.
	.
	.
	.
	.

	1st/Pike
	.
	.
	.
	.
	.
	.
	etc…
</body>
