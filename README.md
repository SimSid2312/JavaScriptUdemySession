# JavascriptUdemySession
Practice Session on JavaScript - Udemy
Tools 
1. IDE - Sublime text
2. The start point of an application (industry standards) should be named 
   - index.html
---------------
 Section -1 ; Lecture 4 : an  example : What Js can do ? 
 When we embed it to Web page to add dynamic content to it.
--------------
Notes for WhereToPutJs.html (Section1 Lecture 5)

1. In head section
2. In body section
3. External file and re-use it in our Html page
(importing the file to HTML)

=>in head tag/ body tag------>

Defining Js in HTML page (can be defined either in head/body tag)
<script type ="text/javascript">
   function myfunction() {
     //content  
   }
</script>

//calling - for instance via a button click-->
<button onclick="myfunction()">Try</button>

Issue:-
difficult to debug when we embed in html ,opt for 3rd option - making a new file extension .js

=>External file (html/js - easy to read and maintain this way)----->

1. create a file - XXXX.js
2. 

function myfunction() {
     //content  
   }
3. calling:
in the calling html 
<script src="xxxx.js"></script>

note - avoid scripting while loading the page i.e in the head tag!
(consideration while performance is criteria)