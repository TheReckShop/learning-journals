#NOTES 11/30/2016

##JAVASCRIPT:

-ALWAYS USE: ‘use strict’; on the first line of code in Javascript

##HTML:

id= :we always sign to single elements, we can only apply ids to a single element, JS manipulates contents of a single element that we have linked with an id tag

class= :we apply to multiple elements, used to apply css among multiple elements

##CSS:

Structure of CSS rules: selector { property: property value; }
example: p {
  color: green;
}
h1 {
  color: blue;
}

In this example p is the selector, color is the property, green is the property value,
In the second example h1 is the selector, color is the property, blue is the property value

Always make a plan or skeleton of what you want your website to do, on paper, then start executing your code according to your plan.

The layout of a website is boxes inside of boxes inside of boxes

class selectors:
.note {} targets any element whose class attribute has a value of note,
p.note {} targets only <p> elements whose class attribute has a value of note

If you have 2 or more CSS rules that apply to the same element THE LAST RULE is the one that will apply i.e. a line 2 rule will be overwritten by the rule on line 100.
Also, if you have a rule

pages 238-240 VERY IMPORTANT FOR CSS

##CSS box model from inside out: content, padding, border, margin

Content: the content of the box where text and images appear
Padding: area between the content and the border padding affected by background color of the box
Border: Border that goes around content and padding. Border is affected by the background color of the box
Margin: the empty area around the border, this area is clear and not affected by the background color of the box

##Javascript:

Control Flow: control flow statement: if, if/else, while, do, for
A single equals sign assign value, to do an equality test use ==, or === so…
= is an assignment operator, DO NOT TEST WITH just = as it is only for assigning value
== test loose equality, loose equality NEVER USE, NEVER EVER
=== tight test, makes sure the things being compared are same value AND same data type

###FOR LOOP:

example:

var samsPets = [‘Buddy’, ‘Alistair’, ‘Trillian’, ‘Demi’, ‘Parker’];

for (var i = 0; i < samsPets.length; i++) {
	console.log(samsPets[i]);
}

###WHILE LOOP:

var nadia = 0;
while (nadia !== 26) {    			
	nadia = parseInt(prompt(‘How old is nadia?’));
}
console.log(‘Nadia is awesome’);

note: ! before == means DOES NOT equal
note: parseInt() turns a string into an numerical data type
