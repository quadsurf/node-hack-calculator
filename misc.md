https://github.com/jkbrzt/httpie
https://github.com/gSchool/javascript-challenges


Suppose a standard 8x8 chessboard has two diagonally opposite corners removed, leaving 62 squares. Is it possible to place 31 dominoes of size 2x1 so as to cover all of these squares?

__

A group of miners in Colorado in the late 19th century are working for a ruthless mining company. The mining company dictates that each day the miners should have exactly 30 minutes for lunch. On top of this, the miners are not provided watches or time keeping devices since the company owners believe they will just get destroyed when the miners inevitably blow their arms off with dynamite or die in some other horrific mining accident. Instead, the miners are given two pieces of rope, but it is no ordinary rope, this rope has the special property that when burned it acts as a timer. Of the two pieces they are given, one piece of rope burns for 15 minutes and the other for 45 minutes. Although the rope acts as a timer, the rope is unpredictable in so much as it does not burn linearly with respect to length and time. Another way to think about this is that if you cut the 15 minute rope into thirds, each third would not burn for 5 minutes, it would instead burn for an indeterminate amount of time. How can the miners use a lighter and these ropes to make sure their lunch is only 30 minutes long?


__

Given an array of integers, find the maximum value in the array.

__

Answer each of the following questions:

Write a function named subtractString that takes a string of arithmetic involving addition and returns the proper value. For example subtractString("10-20-30"); would return -40 (as a Number).
Write a function named divideString that takes a string of arithmetic involving addition and returns the proper value. For example divideString("10/20"); would return 0.5 (as a Number). What is the edge case in division? Do not worry about covering it but please explain what it is.
What are the two fundamental characteristics of Objects?

__

Answer each of the following questions:

Write a function named addString that takes a string of arithmetic involving addition and returns the proper value. For example addString("10+20+30"); would return 60 (as a Number).
Write a function named multiplyString that takes a string of arithmetic involving addition and returns the proper value. For example multiplyString("10*20*30"); would return 6000 (as a Number).
Is it possible to do an inplace swap in a String in JavaScript? How about an Array? Why?

__

Answer each of the following questions:

Write a function named reverse that takes a string argument and returns the string reversed. The string provided as the argument should not be modified.
Write a function named reverse that takes a string argument and returns the string reversed, but this time the string argument should be modified.
What is a closure? Provide an example.

__

Answer each of the following questions:

(multiple choice) Node.js is a:
  a. platform designed for building web applications
  b. web application framework
  c. platform
  d. framework
  e. none of the above
  f. all of the above
Who is Ryan Dahl?
What is fs and why is it important?
How is JavaScript different than Node.js?
Write a Node.js script that takes a command line argument for a filename, then uses fs.readFile and fs.writeFile to produce a copy of the file in which all of the lines have been reversed and the additional extension .reverse has been added. Here is what usage looks like:
  // in foo.txt
  a
  b
  c
  d

  // at the CLI:
  $:> node reverse_file.js foo.txt
  $:> ls
  foo.txt   foo.txt.reverse
  $:> cat foo.txt.reverse
  d
  c
  b
  a
try your best to do this challenge from memory! Bonus points if you can write it by hand first with completely valid syntax.


__


Answer each of the following questions:

What is Function.prototype.call?
Give an example that uses Function.prototype.call.
What is Function.prototype.apply?
Give an example that uses Function.prototype.apply.
What is the difference between Function.prototype.call and Function.prototype.apply?
Create an example of an inheritance hierarchy that uses Function.prototype.call or Function.prototype.apply to reduce duplication in constructor code.

__

Follow the instructions, consider this a small primer for what is to come tomorrow:

Make a directory in your workspace called 'before_enlightenment'. Change into the directory you just created.
run jasmine init
create a file called src.js
add the following to src.js:
module.exports = {
  compact: function(input) {
    // Your code here
  }
}
create a file called spec.js in the spec directory
copy paste the content on this gist to the spec.js file: https://gist.github.com/deitrick/ba9437668e2c9522fe55
run jasmine
crush code



___

Mentally evaluate each of the following code examples, do not use an interpreter:

  function theBest() {
    function theWorst () {
      count -= 4;
    }

    var count = 10;

    function reallyTheBest () {
      count += 25;
    }

    reallyTheBest();
    reallyTheBest();
    reallyTheBest();
    theWorst();
    theWorst();
    reallyTheBest();

    return count;
  }

  console.log(theBest());
1.

  function addN(n) {
    return function(x) {
      return n + x;
    }
  };

  var addSix = addN(6);
  var addTwo = addN(2);

  console.log(addSix(10));
  console.log(addSix(100));
  console.log(addSix(100) + addTwo(10));
What is wrong in the following code example:
  function shouldHire(candidate) {
    bestCandidate = candidate.qualified == 'yes' ? true : false;

    return bestCandidate ? 'Found em!' : 'Continue searching!';
  }
What happens when the following code is entered into a node console or other JS interpreter?
  function greatCodeIsGreat(conditionsForGreatness {
    return 'All Code is Great Code... just kidding!';
  }



___

Implement a function which takes two parameters, both of which are arrays, and zips them together. ie: The arguments are [1,2,3], and [4,5,6], and after zipping the two arrays, you return [1,4,2,5,3,6].

Implement a function which determines whether or not something is in an array. The function should be defined with two parameters, one of which is an array, the other which is either a string or integer. ie: Arguments [1,2,3], and 3, would return true. Arguments [1,2,3], 4, would return false.

Implement a function which determines if an element appears more than once in an array.

__

Write a for loop AND a while that returns the following outputs:

1(odd)
2(even)
3(odd)
4(even)
5(odd)
6(even)
7(odd)
8(even)
9(odd)
10(even)
Conference 1:
Team 1
Team 2
Team 3
Team 4
Conference 2:
Team 1
Team 2
Team 3
Team 4
Conference 3:
Team 1
Team 2
Team 3
Team 4
Conference 4:
Team 1
Team 2
Team 3
Team 4
11 times 1 equals 11
11 times 2 equals 22
11 times 3 equals 33
11 times 4 equals 44
11 times 5 equals 55



https://gist.github.com/mjhea0/0ef22d0e81bf07a2ccc0


___

Suppose you're in a hallway lined with 100 closed lockers. You begin by opening every locker. Then you close every second locker. Then you go to every third locker and open it (if it's closed) or close it (if it's open). Let's call this action toggling a locker. Continue toggling every nth locker on pass number n. After 100 passes, where you toggle only locker #100, how many lockers are open?

__

Sequence Diagrams of Mongo / Express
Draw a sequence diagram of your app making a POST request to a create route that:

inserts data
redirects to the show route
the show route pulls data from mongo and renders it with jade
Fork, clone and create a pull request here: https://github.com/gSchool/sequence-diagrams

Add your solution to the express-mongo-get-index/diagram.md document.


__

Write the SQL create table statments for the homework last night. You should have a books table and an authors table. Your statments should look like:

CREATE TABLE ...

Write a select statement that gets all the books for a certain author. For example, all the books that the first author made.

__
