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
      }

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
        }
        password: 'asdf123',
      }
      
      what happened here is that before, the object user had no key value pair named password, where as after writing user.password = 'asdf123' added the key value pair of password with value of 'asdf123'
