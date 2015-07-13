1) primitives - five of 'em'
- strings   - numbers   -booleans   - null    - undefined


2) functions

expression syntax
var functionOrVariableName = function () {
    code to execute
}

Declaration syntax
function functionName() {
    code to execute
}

Returns
- unless you state RETURN the function won't give you back any info
- RETURN breaks out of the function; any code following return won't be executed
- set return equal to a variable so you can use that data, you have a handle to it

Parameters / Arguments

function Sum(x, y)  <- Parameters
    parameters are when you define/declare/express the function
Sum(4, 5)  <- Arguments
    arguments are when you call the function


3) Loops

   for (var i = 0; i < 10; i ++)
        var i = 0    where you start
        i < 10       where you end
        i ++         the loop increment
   for (start; stop; change)

   WHILE loop
    - continues to do something while any condition is true
    - will keep going until that condition is met.

    while (true) {
      code to execute
    }


4) Conditionals

  if( condition ) {
     do this code;
  } else if {
     do this code;
  } else {
      do this code; (DEFAULT Behavior of this statement)
  };


5) VARIABLES
- it is a stored value
- create by calling, var varName = yourValue
- can be changed any time by just stating, the varName again and setting it to a new value.

    VARIABLE SCOPE
    - Global
        - defined outside of any function.
        - can be used/accessed anywhere in the script
    - Local
        - declared/defined within a function
        - only accessible by/within the function  
        - meaningless outside of the function
        - RESET every time that function is called
        - you can store a local variable inside a global variable by declaring a variable equal to the return of that function

          var Global = 1
          function() {}
              LocalVariable
          }

          GlobalVariable = function() with local variale inside it.
          var new Global = function() with local

          var sum = "2";

          function add (){
            var secondNum = 2;
            return 2+secondNum;
          }

          sum = add();
          var newSum = add();
          ]

      HOISTING
        - when you don't declare a local variable so the function looks for the variable globally
        - the way to solve this is to ALWAYS use VAR when declaring/changing a variable.

7) ALERTS & PROMPTS
PROMPTS
- Popup input box
- always return a strings

ALERT
- just sends the user message in a popup format

CONFIRM
- asks the user to confirm OK or CANCEL
- OK returns Boolean TRUE, canel returns Boolean FALSE


8) String Concatenation

- Variable +=
- Variable = Variable + "Something"
- you can Concatenate with different types of primitives  
    "String " + 2 + " this is your string"


9) String, Integar Methods
- like functions that you append to the string with a .
- array.length
- array.charAt(parameters)



10) Math Operators
+ , - , * , / , > , < , => , <=


MARKDOWN CHEATSHEET
# = H1
## = H2

**something** = BOLD
*something* = ITALIC
link text[link.url] = link
! link text [ img ] = link to an image

'''Javascript          this formats code
var text = 7
'''

ordered list
* something
* something
* something

ordered list
1. something
1. something
1. something

Tables
- tablegenerator.com

>test   -block quote

Cheat sheet for githug markdown info
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
