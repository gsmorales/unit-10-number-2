# unit-10-number-2
CS 81
<!DOCTYPE html>
<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script>
$(document).ready(function(){

   /* Button with id btn1 click event */
   $("#btn1").click(function(){
       /* Appending text at the end of <p> tag */
       $("p").append("<b>Appended text.</b>");
   });
  
   /* Button with id btn2 click event */
   $("#btn2").click(function(){
       /* Appending list item at the end of <ol> tag */
       $("ol").append("<li>Appended item</li>");
   });

});
</script>
</head>
<body>

<p> This is a paragraph.</p>
<p> This is another paragraph.</p>

<ol>
    <li> List item 1</li>
    <li> List item 2</li>
    <li> List item 3</li>
</ol>
  

<button id="btn1">Append text </button> 
<button id="btn2">Append list items </button>

</body>
</html>
