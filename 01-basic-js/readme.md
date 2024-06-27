what is javascript and why we used it ? 

- javascrpt is logic based programming language where we can create our code project functionality in that.
- javascrpt is a high level programming language for build web pages.
- Now we used the ES6(echma script 6) version of javascript, in other words we called vanila javascript. 
- runtime environment of javascript is node js.

variable :- 

- varible is container to store some data. 
- in javascript we have 3 types of variables
1. let :-
    - Let is a type of variable which is used for changing the varibale name later.
    - Now these days , most of the cases we used let for creating varibale.
    - Let is a block scope code so we have been using let for most of the cases.
2. var :-
    - Var is a type of variable which is also used for changing the variable later stage.
    - Var is used in oldest browser so now a days we are dont use var most of the time.
3. const :- 
    - const is a type of varible where we can't change our data further.
    - const means constant to store some data like numbers, integer etc..


task :- 
1. difference between let & var. 
2. Difference between var & const. 
3. what do you mean by haisting. (when we dont declare value of varibale but it execute the code)


Rules of Variable :- 

- Variable names are case sensative "a" & "A" is different.
- Only letter, digit, underscore & $ is allowed. (not even space).
- only letter, underscore or $ should be 1st character.
- reserver words cannot be variable names.

data types in javascript :-

- data type is an attribute associated with a piece of data that tells a computer system how to interpret its value.
- in data types we used "typeof" operator to know the what type of data it is.
- mainly in javascript their are 2 types of data type. 

1. Primitive:- 
    - in javascript there are 7 types of primitive data types. 
    1. Number :- number are the type of data type those it contain some numerical value. 
    2. String :- String is a type of data type that can hold some character like names... 
    3. Boolean :- In boolean data type we get Boolean value like true, false
    4. Undefined :- in undefined data type the data is not define so that it will show undefined.
    5. Null :- In this data type we get null for the value means nothing
    6. Bigint :- in bigint we will get big integer 
    7. Symbol :- in symbol we will get whole symbol as well as the value we get for the data type.

2. Non-primitive or Reference 
    - non primitive data types are the type of data type that can hold multiple items in a singke time
    - non-primitive data types are - object, array, function
    object :- 
        - object is a non-primitive data types which can hold multiple of item in one single entity.
        - mainly objects are working on (key:value) pair.
        - The left hand side is our keys and right hand side are the values of the following object.

        ex - 

        prathama = {
            college : "GIET",
            address : "BBSR",
            age : 48,
            salary : 45000,
            carrier : "Good"
        }

Operator in JS :- 
- operator are the key features to do some task or operate some task.
- ex. A + B 
- in the above example A & B are the operands , '+' is the operators to do the addition. 
1. Arithmetic Operators:- 
   (+,-.*,/)
   modulus -> %
   Exponentiation -> **

2. unary operator:=
   increament -> ++
   decrement -> --

3. assignment operator :- (assign some value to the variables)
   (=, +=, -=, *=, %=, **=)

4. Comparison operator :- (compair the values)
   * its give the eresult true or false.
   equal to -> ==
   not equal to -> !=
   equal to & type -> ===
   not equal to & type -> !==
   (>, >=, <, <=)

5. Logical Operator :- checks the logic of the operator(true/false)
   Logical AND &&
   table of AND operator is :- 
   cond 1 , cond 2, res (&&)
   T + T = T
   T + F = F
   F + T = F
   F + F = F
   Logical OR ||
   Table of OR operator is :- 
   cond 1 , cond 2, res (||)
   T + T = T
   T + F = T
   F + T = T
   F + F = F
   Logical NOT !

conditional statement :- 

- to implement some condition in the code 
- there are 3 types of conditional statements are there 
1. if condition -
    - if condition is true then statement is true otherwise false.
    syntax :- 
    if(condition){
        statement
    }
2. if-else condition
    - if condition is true then block executed otherwise its terminate to else condition.
    syntax :- 
    if(condition){
        statement
    }
    else{
        statement
    }
3. else-if condition 
    - its check the condition multiple times where condition is true.
    syntax :- 
    if(condition){
        statement
    } else if(condition) {
        statement
    } else if(condition) {
        statement
    } else {
        statement
    }
LOOPS IN Javascript :- 

-loops are used to execute a piece of code again and again.
1. For loop :-
 syntax - for (initialization,condition,updation){
    statements
 }

 example ---
 
  for(let i = 1; i <= 5 ; i++>){
    console.log("web bocket")
 }

 output - 

 web bocket
 web bocket
 web bocket
 web bocket
 web bocket


2. While loop :-
 syntax -
 while(condition) {
    statement
    updation
 }

 3. Do-while :-
 syntax-
 do{
    statement
    updation
 } while (condition);

 4. For-of loop :-
 -- It iterate an string and array
  
  5. for-in loop - 
  -- iterate over objects(key-value pair)
   syntax - 
   for(let key in objvar){
    statement
   }

   * home work*
   1. print all even number from 0 to 100
   2. crate a game you start with any random number. ask the user to keep guessing the game number untill the user enters correct value.

   String in JS :-

-String is a sequence of characters used to represent text.

-create a string -> let str = "web bocket

-string length -> str.length

-string indexing -> str[0], str[1], str[2]....

Template literals in JS :-
- a way to have embeded expression in string.
- it denoted on `` , i.e `today is a great day`

String Interpolation :-
- to create strings by doing substitution of placeholders.
ex -> `string text${expression} string text`

escape symbol :-
\n - new line
\t - tab inside the test

String Methods :--
-these are built in functions to manipulate a string.
1. str.toUppercase()
2. str.toLowercase()
3. str.trim()
4. str.slice(start, end)
5. str1.concat(str2)
6. str.replace(searchVal , newVal)
7. str.chatAt(idx)