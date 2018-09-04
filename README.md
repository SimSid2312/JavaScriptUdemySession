# JavascriptUdemySession
Practice Session on JavaScript - Udemy
Tools 
1. IDE - Sublime text
2. The start point of an application (industry standards) should be named 
   - index.html
***********************
Section -1 ; Lecture 4 : an  example : What Js can do ? 
When we embed it to Web page to add dynamic content to it.

1. JS can change the content of HTML.
2. JS can change the attributes of HTML tag.
3. JS can show/hide content of HTML.
***********************
  (Section1 Lecture 5) :Notes for WhereToPutJs.html

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
***********************
Section-2 Lecture 1 : Notes for How to See Output from JS

Four Ways :
1. window.alert() - Throws alert on the window for the user.A Method;accept input parameters
2. document.write() - Used to write/update data on screen.A Method;accept input paramters
3. innerHTML - Used to update the text in HTML.Just do assignment for this.
4. console.log() - Important for development purpose ; Works silently without hindering user experience.A Method;accept input parameters.

Important point :
- using document.write after page loads will replace the content of the page(Must be avoided).
- to see the output for console.log - on browser > rt. click and click on inspect > console 
