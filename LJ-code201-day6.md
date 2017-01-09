# Notes for 1/9/2017

## Key value pairings

    var user = {
      userName: 'davidC',
      age: 30,
      email: 'thereckshop@mac.com',
    }

    In this example a key value pair is userName and davidC
    - the userName is the key that allows you to access the string of davidC
    - It follows then that another key value pairing is age and 30, where they value is 30 and the key is age  

THERE IS ONLY EVER ONE KEY WITH ONE VALUE PER KEY VALUE PAIRING

## Methods
A method is a function that is paired to a specific object

- example:

      var user = {
        userName: 'davidC',
        age: 30,
        email: 'thereckshop@mac.com',

        login: function(){
        console.log(userName + ' logged in!');
        }
      };

      In this example the object user has a method name login that is the function console.log(userName + ' logged in!');

To add more key value pairs to an object called user one would write:

      user.password = 'asdf123'
      - the resulting effect of this on the object user is as follows

      var user = {
        userName: 'davidC',
        age: 30,
        email: 'thereckshop@mac.com',
        login: function(){
        console.log(userName + ' logged in!');
        },
        password: 'asdf123'
      };

      what happened here is that before, the object user had no key value pair named password, where as after writing user.password = 'asdf123' added the key value pair of password with value of 'asdf123'

## The DOM

Elements in the DOM can be accessed by typing document.getElementsById or document.getElementsByClassName or other such variations.

Basically in web development the object 'document' access the whole html or JS document

To put more stuff on the screen:
1. create the element you want to add
2. add content to that element by defining its attributes
3. append that element as a child of its parent
        html code: <ul id= "my-list"> </ul>

        var names = ['Adam', 'Wilson', 'Sea', 'Hawkz'];

        var mylist = document.createElementById('my-list');

        for(var index = 0; index < names.length; index++){
          var listElement = document.createElement('li');
          //step one!

          listElement.setAttribute('class', 'my-list-item');
          listElement.textContent = foods[index] + '- index: ' + Index;
          // step 2!

          myList.appendChild(listElement);
          //step 3!

        }
