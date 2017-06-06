# HTML-elements
The often used elements

// part 1
<h1>some title..</h1>,  <h2>, <p></p>

//Use CSS Selectors to Style Elements 
  <h2 style="color: blue">TitleName</h2> //not in CSS
-------------
  //in html
  <style>
    h2 {color: blue;}
  </style>
----------------
// in CSS
  h2 {
  color: blue;
  }
  
  //name a class and set in CSS
   .red-text {
    font-family: Helvetica, Sans-Serif;  // if first not work, go second one
    font-size:16px;
    color: red;
    background-color: silver;
  }
  //import google font
  <link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
  
// image
<img class="imgclass .thick-green-border" src="https://www.your-image-source.com/your-image.jpg" alt="Author standing on a beach with two thumbs up. ">
  // in css
  .imgclass{width:100px;}
  .thick-green-border{
    border-color: green;
    border-width: 10px;
    border-style: solid;
    border-radius:10px;  // or try 50% 
  }
  #idName{
  }
//link
  <p>Here are <a href="#">cat photos<img src="" alt=""></a><p>
  //list: ul, ol
  <ul>
    <li></li>
    <li></li>
    <li></li>
  </ul>
// input and send data to database
<form action="/submit">
  <input type="text" placeholder="write something" required> // required is optional
  <button type="submit">submit</button>
</form>  
//radio,checkbox button
  <label><input type="radio" name="indoor-outdoor" checked>Indoor</label>
  <label><input type="checkbox" name="personality"> some</label>
//padding, margin
//An element's padding controls the amount of space between the element and its border.
//An element's margin controls the amount of space between an element's border and surrounding elements.
.red-box {
    background-color: red;
    margin-top: 40px;
    margin-right: 20px;
    margin-bottom: 20px;
    margin-left: 40px;
    padding-top: 40px;
    padding-right: 20px;
    padding-bottom: 20px;
    padding-left: 40px;
    border-style: solid;
    border-color: black;  // or #000000 or #000 or rgb(0, 0, 0)
    border-width: 5px;
    text-align: center;
    color: pink!important;
  }

