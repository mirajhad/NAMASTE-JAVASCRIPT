# NAMASTE-JAVASCRIPT

1. JavaScript is Synchronous Single-Threaded language.

2. Its execute in two phase:-
a. Memory Component.
b. Code Componenet.



3. Hoisting:-

4. variable are declare before running the program. example:-

console.log(b);
let a = 10;
var b = 100;

5. strict

const>let>var

6. In case of const initialize and declare at same time example:-

const a = 10;


7...
0. Call stack
1. Execution Stack
2. Program Stack
3. Control Stack.
4. Runtime Stack.
5. Machine Stack.

8. Hoisting




9. Lexical Environment:- its is a local memory along with lexical environment of its parents.




10. Closure:-

A function with lexical scope form closure.

function z(){
	var b = 900;
	function x(){
	var a = 7;
	function y(){
	 console.log(a,b);
	}
	y();
	}
	x();
	}
	z();
	
11. Uses of Closure:-
--Module Design Pattern
--Currying
--Functions like once
--memoize
--maintaining state in async world
--setTimeouts
--Iterators
--and many more...


12. Disadvantage of closure:-
It occuiped more space


13. Function Statement:-
function a(){
	console.log("a");
		}

14. Function Expression:-

var b = function a(){
	console.log("a");
		}

15. Anonymous Function:-

function(){

}


16.Named Function Expression:-

var b = function xyz(){
	console.log("b called");
	}

b();


17.Callback Function:-

By callback we can do asynchronous thing in js.
 

astexplorer.net

18. JavaScript engine V8


19. Trust issue with SetTimeout


20. High Order Function
A function with takes an function as argument or return is known as HOF.


///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

MountBlue

1. regular Expression test(),match(),search(),


2. var inputString ="This is computer";
var regexp = /computer/
console.log(regexp.test(inputString));

true

3. var inputString = "this is computer or a ball";
var regexp=/computer/ball/ig
console.log(inputString.match(regexp));
console.log(inputString.search(regexp));


4. wildcard
var inputString = "fun, car, gun, funny";
var regexp = /.un/g
console.log(inputString.match(regexp));

5. var inputString = "fFunny";
var regexp = /[a-z]/g
console.log(inputString.match(regexp));


6. var inputString = "fFunny 12243";
var regexp = /[a-z]| [0-9]{4}/g
console.log(inputString.match(regexp));


\d -- [0-9]
\D -- [^0-9]
\w -- [A-Z a-z 0-9_]
\W -- [^A-Z a-z 0-9_]
\u -- unicode*/
\w+ - one or multiple 
\w* -- zero or multiple
