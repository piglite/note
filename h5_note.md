## Chapter 1 Getting to know HTML5:Welcome to Webville ##


1. some tags get clean and easy write from HTML4.01 to HTML5

>    

	
	4.01 <!DOCTYPE html  PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
    
	5.0  <!DOCTYPE html>

	4.01 <meta http-equiv="content-type" content="text/html; charset=UTF-8">

	5.0  <meta charset="utf-8">

	4.01 <link type="text/css" rel="stylesheet" href="main.css">

	5.0  <link rel="stylesheet" href="main.css">

  
    
> 

2. what is HTML5?
   
   **Markup + Javascripts APIs + CSS = HTML5**

## Chapter 2 Introducing Javascript and the DOM: A Little Code ##

1. use var declare a variable but no value, the variable now is undefined. And you can give the value null to a variable, that's mean "no value".
2. Javascript dose have type, but Javascript has dynamic type, which menas that you don't have to specify a type and the Javascript interpreter will figure out what type to use as code running.
3. how to name a variable:
	-    start with a letter, an underscore(_) or a dollar sign($)
	-    begin with number not good(but can)
	-    begin with symbols aren't allowed
	-    the name got a space is not allowed
	-   the name got -,+ sign is not allowed. these signs will seriously confuse Javascript
	-   make sure avoid all of Javascript's reserved words
4. guide to better numing
  - choose names that mean something
  - use camel case when creating multiword variable names
  - start with _ and $ only wity very good reason

5. statement and expression 
 
	![javascript statement](http://p1.bqimg.com/4851/8da2fac0c3e2da77.png)

6. some expression

    ![boolean expression](http://p1.bqimg.com/4851/f5fa53d56af3064d.png)
	
	![numeric expression](http://p1.bqimg.com/4851/6b9eabea12337352.png)
	
	![string expression](http://p1.bqimg.com/4851/c954b2cfe745f113.png)

	![other expression](http://p1.bqimg.com/4851/b7d75b9c6ad3df0e.png)

7.	where to add JavaScript code to pages

    - place in the <head> element. type the code or refreence separate JavaScript file using the src attribute. the code executed as soon as the browser parses the head(which is does first!) before it has parsed the rest of page.
    - 