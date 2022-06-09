<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SSB H.W</title>
    <style>
        fieldset {
          background-color: #eeeeee;
        }
        
        legend {
          background-color: gray;
          color: white;
          padding: 5px 10px;
        }
        
        input {
          margin: 5px;
        }

        figure {
          border: 1px #cccccc solid;
          padding: 4px;
          margin: auto;
          }

        figcaption {
         background-color: black;
          color: white;
          font-style: italic;
          padding: 2px;
          text-align: center;
        }
        </style>

</head>
<body>
    h1>The fieldset element</h1>

<form action="/action_page.php">
 <fieldset>
  <legend>Personalia:</legend>
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <label for="lname">Last name:</label>
  <input type="text" id="lname" name="lname"><br><br>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email"><br><br>
  <label for="birthday">Birthday:</label>
  <input type="date" id="birthday" name="birthday"><br><br>
  <input type="submit" value="Submit">
 </fieldset>
</form>


<br><br><br>


<h1>The fieldset element + CSS</h1>

<form action="/action_page.php">
 <fieldset>
  <legend>Personalia:</legend>
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <label for="lname">Last name:</label>
  <input type="text" id="lname" name="lname"><br><br>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email"><br><br>
  <label for="birthday">Birthday:</label>
  <input type="date" id="birthday" name="birthday"><br><br>
  <input type="submit" value="Submit">
 </fieldset>
</form>

<br><br><br>

<h1>The embed element</h1>

<embed type="image/jpg" src="pic_trulli.jpg" width="300" height="200">

  <h1>The embed element</h1>

<embed type="text/html" src="snippet.html"  width="500" height="200">

  <embed type="video/webm" src="movie.mp4" width="400" height="300">

    <br><br><br>

    <h1>The dl, dd, and dt elements</h1>

<p>These three elements are used to create a description list:</p>

<dl>
  <dt>Coffee</dt>
  <dd>Black hot drink</dd>
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl>
<br><br><br>

<h1>The em element</h1>

<p>You <em>have</em> to hurry up!</p>

<p>We <em>cannot</em> live like this.</p>


<br><br><br>

<h1>The div element</h1>

<div style="border: 5px outset red;
  background-color: lightblue;    
  text-align: center; ">
  <h2>This is a heading in a div element</h2>
  <p>This is some text in a div element.</p>
</div>

<p>This is some text outside the div element.</p>
<br><br><br>

<h1>The dialog element</h1>

<p>This is some text.</p>

<p>This is some text.</p>

<dialog open>This is an open dialog window</dialog>

<p>This is some text.</p>

<p>This is some text.</p>

<p><b>Note:</b> The dialog tag is not supported in Safari and Edge (prior version 79).</p>

<br><br>

<p><dfn>HTML</dfn> is the standard markup language for creating web pages.</p>
<br><br>
<p><dfn title="HyperText Markup Language">HTML</dfn> is the standard markup language for creating web pages.</p>
<br><br><br>

<h1>The details element</h1>

<details>
  <summary>Epcot Center</summary>
  <p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.</p>
</details>


<h1>The del element</h1>

<p>My favorite color is <del>blue</del> <ins>red</ins>!</p>


<br><br><br>

<!DOCTYPE html>
<html>
<body>

<h1>The datalist element</h1>

<form action="/action_page.php" method="get">
  <label for="browser">Choose your browser from the list:</label>
  <input list="browsers" name="browser" id="browser">
  <datalist id="browsers">
    <option value="Edge">
    <option value="Firefox">
    <option value="Chrome">
    <option value="Opera">
    <option value="Safari">
  </datalist>
  <input type="submit">
</form>

<p><strong>Note:</strong> The datalist tag is not supported in Safari 12.0 (or earlier).</p>
<br><br><br>

<h1>The data element</h1>

<p>The following example displays product names but also associates each name with a product number:</p>

<ul>
  <li><data value="21053">Cherry Tomato</data></li>
  <li><data value="21054">Beef Tomato</data></li>
  <li><data value="21055">Snack Tomato</data></li>
</ul>

<br><br><br>

<h1>The form element</h1>

<form action="/action_page.php">
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <label for="lname">Last name:</label>
  <input type="text" id="lname" name="lname"><br><br>
  <input type="submit" value="Submit">
</form>

<p>Click the "Submit" button and the form-data will be sent to a page on the 
server called "action_page.php".</p>
<br><br>


<h1>The figure and figcaption element</h1>

<figure>
  <img src="pic_trulli.jpg" alt="Trulli" style="width:100%">
  <figcaption>Fig.1 - Trulli, Puglia, Italy.</figcaption>
</figure>


<br><br>

<h1>Form with checkboxes</h1>

<form action="/action_page.php" method="get">
  <input type="checkbox" name="vehicle1" value="Bike">
  <label for="vehicle1"> I have a bike</label><br>
  <input type="checkbox" name="vehicle2" value="Car">
  <label for="vehicle2"> I have a car</label><br>
  <input type="checkbox" name="vehicle3" value="Boat" checked>
  <label for="vehicle3"> I have a boat</label><br><br>
  <input type="submit" value="Submit">
</form>
<br><br>
<h1>Form with radio buttons</h1>

<form action="/action_page.php" method="get">
  <input type="radio" id="html" name="fav_language" value="HTML">
  <label for="html">HTML</label><br>
  <input type="radio" id="css" name="fav_language" value="CSS" checked="checked">
  <label for="css">CSS</label><br>
  <input type="radio" id="javascript" name="fav_language" value="JavaScript">
  <label for="javascript">JavaScript</label><br><br>
  <input type="submit" value="Submit">
</form>


<br><br><br><br></br>

<h1>The footer element</h1>

<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>

<p><b>Tip:</b> Use h1 to h6 elements only for headings. Do not use them just to make text bold or big. Use other tags for that.</p>
<br><br>
<h1 style="text-align:center">This is heading 1</h1>
<h2 style="text-align:left">This is heading 2</h2>
<h3 style="text-align:right">This is heading 3</h3>
<h4 style="text-align:justify">This is heading 4</h4>

<br><br><br>
<h1>The Main Languages of the Web</h1>

<p>HTML is the standard markup language for creating Web pages. HTML describes the structure of a Web page, and consists of a series of elements. HTML elements tell the browser how to display the content.</p>

<hr>

<p>CSS is a language that describes how HTML elements are to be displayed on screen, paper, or in other media. CSS saves a lot of work, because it can control the layout of multiple web pages all at once.</p>

<hr>

<p>JavaScript is the programming language of HTML and the Web. JavaScript can change HTML content and attribute values. JavaScript can change CSS. JavaScript can hide and show HTML elements, and more.</p>

<br><br><br>

<h1>The i element</h1>

<p><i>Lorem ipsum</i> is the most popular filler text in history.</p>

<p>The <i>RMS Titanic</i>, a luxury steamship, sank on April 15, 1912 after striking an iceberg.</p>
<br><br><br>

<h1>The iframe element</h1>

<iframe src="https://www.facebook.com" title="W3Schools Free Online Web Tutorials">
</iframe>

<br><br>

<h1>The iframe height attribute</h1>

<iframe src="/default.asp" width="200" height="200">
<p>Your browser does not support iframes.</p>
</iframe>

<br><br><br>

<h1>The ins element</h1>

<p>My favorite color is <del>blue</del> <ins>red</ins>!</p>

<br><br>

<br><br><br>
<h1>The ol and ul elements</h1>

<p>The ol element defines an ordered list:</p>
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

<p>The ul element defines an unordered list:</p>
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

<h1>The kbd element</h1>

<p>Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to copy text (Windows).</p>

<p>Press <kbd>Cmd</kbd> + <kbd>C</kbd> to copy text (Mac OS).</p>

<br><br><br>

<br><br><br>

<h1>The main element</h1>

<main>
  <h1>Most Popular Browsers</h1>
  <p>Chrome, Firefox, and Edge are the most used browsers today.</p>

  <article>
    <h2>Google Chrome</h2>
    <p>Google Chrome is a web browser developed by Google, released in 2008. Chrome is the world's most popular web browser today!</p>
  </article>

  <article>
    <h2>Mozilla Firefox</h2>
    <p><mark>Mozilla Firefox is an open-source web browser developed by Mozilla. Firefox has been the second most popular web browser since January, 2018.</mark></p>
  </article>

  <article>
    <h1>Footer</h1>
    <h2>Microsoft Edge</h2>
    <p>Microsoft Edge is a web browser developed by Microsoft, released in 2015. Microsoft Edge replaced Internet Explorer.</p>
  </article>
</main>


<footer>
  <p>Author: Hege Refsnes<br>
  <a href="mailto:hege@example.com">hege@example.com</a></p>
</footer>


</body>
</html>





</body>
</html>
