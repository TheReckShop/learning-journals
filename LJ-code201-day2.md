# Notes for 1/3/17

## HTML

### Semantic HTML:
It uses tags with the meaning of the word as in the feel of the content, not what to do to them exclusively
For example: <i></i> IS NOT a semantic tag.
<em></em> IS a semantic tag because.

### HTML Class vs ID
Class is used to process broader elements using our class tag
for Example * {
		color: red
		}
This would color the whole page red because * is a class selector that represents everything
ID is used to select one SINGLE object
EXAMPLE:
<p class="paragraph" id="madDeep">Mad deep paragraph yo!</p>
    <p class=“paragraph” id=“hellaShallow”>Hella shallow paragraph yo!</p2>

## GIT

commands:

git checkout existentBranchName
-This checks out the existent branch on your computer.

git checkout -b newBranchBeingCreated
-This creates a new branch and then moves into it.

git branch
-This will list any and all branches in the repository

git add / git add .
-Stage the change you have made to the branch that (git add . selects and adds ALL changes)

git commit -m ‘the message you want about the commit’
-This commits the changes to your branch on your computer

git push origin branchName
-Pushes up to repo on gitHub where the work will be saved to the specified branch

git mv testNameFileToBeChanged newTestNameFileYouWant
-Renames your file be deleting old and creating new file with exact same contents and git history



##Javascript Arrays

An array is a series of different value types into their own type (called a selectionType) that can be assigned to one variable
In other words an ordered list of data
EXAMPLE: var testArray = [‘p’,5,7,8]
The first element of this array is the string ‘p’, the second is 5, and so on
To select the number 8 out of this array you would do testArray[3] would return the value of 8 because arrays ALWAYS USE 0  AS THE FIRST VALUE IN AN ARRAY

### Javascript commands for arrays
testArray.shift(newData) /  testArray.unshift()
.shift(newData): array now adds whatever newData is to testArray AT THE BEGINNING
.unshift removes whatever the first value in the Array is
testArray IS JUST A NAME COULD BE NAMED ANYTHING!

testArray.push(newData) / testArray.pop()
.push(newData) adds whatever newData is TO THE END of testArray
.pop() removes THE LAST VALUE in testArray
testArray IS JUST A NAME COULD BE NAMED ANYTHING!

### ALWAYS START JS DOCUMENT WITH THE STRING: ‘use strict’
