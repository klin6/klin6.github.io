---
layout: essay
type: essay
title: Learning A New Power
# All dates must be YYYY-MM-DD format!
date: 2018-08-31
labels:
  - Javascript
---

## Mind Blowing Script

It’s already been about two weeks since I’ve been introduced to Javascript and honestly speaking it is a bit different to what I was initially expecting. Before taking ICS 314, I thought Javascript was just going to be like Java only at a more difficult level. After the past two weeks I can tell why Javascript is one of the three core technologies of the World Web. Up to now I have learned Java, C, and C++, but compared to these Javascript is much more powerful. It’s powerful because I don’t have to declare my variables datatypes like int, float, double, char, or string. Which is something less trivial to worry about.

<div>
<img class="ui small left floated rounded image" src="../images/arm.jpg">
</div>

## Hello FreeCodeCamp

<img class="ui small right floated rounded image" src="../images/FCC.jpeg">

Personally when it comes to me having to learn a new language I have the consistency in thinking that I’m learning to code all over again. So when my professor provided the code practicing website “FreeCodeCamp”, it was very educational. This was a very helpful introductory to start with in Javascript, because it showed me some basics that I’m familiar with or Javascripts’ adaptations of them. For instance I thought it would be closely similar to Java in using “System.out.println()” but instead it uses a browser’s display called “console.log()”. I also discovered that operators are slightly different from C and C++. Usually it’s using “!=“ to define conditions as not equal but in Javascript it’s “!==“, there’s an extra equal sign. If I didn’t complete FreeCodeCamp’s basic Javascript tutorial I wouldn’t have known how to start in this new language I’m learning.

## Power Mind Training

Along with starting how to use Javascript I was also challenged with “athletic software engineering”. It’s basically speed coding on new material that I presently learned. This type of style of learning so far has refreshed my mind after not touching up on coding from a long three month summer break. I think this is an excellent strategy because it will get me ready for when I want to look for a job since Javascript is majorly used in professional work environments. 

Because each time is like a brain workout, my professor calls it a Workout of the Day (WOD). My first WOD was the temperature converter, a very simple implemented function which I could have made average time, but I missed out on the fact that I switched the temperatures arguments. But if I keep repeating to practice the WODs again and again, I predict that I’ll gain a new strength in my own software abilities.

<pre>
	function temperatureConverter(temp, tempType){
		switch(tempType){
  		case 'C': 
    		case 'c':
    			return (temp-32)*(5/9);	//1. wrong argument
    		case 'F':
    		case 'f':
    			return (temp*(9/5))+32;	//2. wrong argument
    		default:
    			return "Illegal temperature type";
  		}
	}
	console.log(temperatureConverter(212, "F"));
	console.log(temperatureConverter(0, "C"));     
	console.log(temperatureConverter(0, "X"));  
</pre>
