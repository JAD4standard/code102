EDITS for pull practice Friday
true vs false
watch for in if statements
truthy        falsey
1             0
'thursday'    undefined
8             null
28.65
'false'

2 == "2" loose compare can we cast these to be equal?  equalish

2 === "2" strict compare = false

parsINT("2") === 2 true

dry
don't repeat yourself

1) Make it run then make it right then make it fast (pretty)
2) When improving it - don't repeat yourself, to dry up code look for lines of code taht are identical or have very little variation try to do each thing only one time.

general syntax for function
function () {...}
named functions
if you want to name the function when you declare it
function doSomethingName(){.not as common in contemorary javascipt..}

  hoisting when javascript script is compiled chunks are getting pulled out & created in memory first so it can be called anywhere.

anonymous function more common in frameworks
var doSomethingvar = function () {...}
not hoisted gets created when execution hits this code

both called (invoked) the same way basically
doSomething(); >> the parens tell compiler to invoke the function

iife - for make use of a function once immediatel invoke function expression
(function(){...}());  
so basically no name, may use to encapsulate your code
