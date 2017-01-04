# Learning Journal 1/4/17

## HTML Lists

#### To make an unordered list use the < ul> < /ul> tags

- < li> < /li> is used to make items within a list that is then represented with a bullet
- much like this markdown note looks

#### To make an ordered list use < ol> </ ol>
- This makes all < li> items within the ordered lists have numbers and order assigned to them

#### To make definition lists use < dl> < /dl>
- use < dt> < /dt> to set the term being defined as that between the tags
- use < dd> < /dd> to set text within them as the definition

## HTML BOXES

### MARGIN BORDER PADDING CONTENT

#### MARGIN:
- The Border between the outside of a box element and the next margin of a box element

#### BORDER:
- The (sometimes visible border) between the MARGIN and the PADDING of a particular box element

#### PADDING:
- The distance between the the CONTENT and the BORDER of a box element

#### CONTENT:
- The actual CONTENT of a box element

## JAVASCRIPT LOOPS

#### FOR LOOPS

example: FOR LOOP
- for(var index= 0; index < 10; index++)
{

  console.log(index);  
}

- what this loop will do is run over and over again adding +1 to i until it reaches 10 at which case it stops

#### WHILE LOOPS

While X is happening continue to run this loop
- Example: WHILE LOOP
- var index = 100;

  while(index > 0) {

    console.log('the index of the while loop is', 0);

  }

#### DO WHILE LOOP

same as while loop but code is while loop will always run at least once, by not evaluating condition until code is run once
- Example: DO WHILE LOOP
- var index = 10;
  - do {

    console.log('Do-while loop fired with index:', index);

  } while (index > 100);
