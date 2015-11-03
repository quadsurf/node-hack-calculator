# Daily Warmups

> Programming challenges are great for daily warmups. Instead of inventing them the night before, reference this repo to find an appropriate challenge for your students.

Warmups are divided into their respective topics. This is useful because you may want to grab different kinds of warmups during different times in a cohort. There is ​*no*​ imposed order to these.

Just grab the one you think is most fitting at any given time!

## Want more?

* [Michael Herman's stash of programming exercises](https://github.com/mjhea0/programming-exercises)
* [Code Problems](https://github.com/blakeembrey/code-problems)
* [Rosetta Stone](http://rosettacode.org/wiki/Rosetta_Code)
* [Javascript coding challenges and interview questions](https://github.com/kolodny/exercises)
* [Recursion exercises](http://roman01la.github.io/recursion-exercises/)
* [5 Interview Questions on Node.js](http://www.codingdefined.com/2015/10/5-interview-questions-on-nodejs.html)

## Todo

There are 68. We should have AT LEAST 120 in here.

## Updating Readme.md:

If you add or modify markdown files in the subdirectories, just run this from the parent dir to regenerate all the readmes:

```for dir in *; do (if [ -d $dir ]; then cd $dir && rm readme.md; awk 'FNR==1{print "\n***\n"}1' *.md > readme.md; fi); done```
