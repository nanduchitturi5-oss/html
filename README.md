<DOCTYPE> 
    <html>
        <head>
            <body>

            
<b>warning:</b>Dont touch the switch board
    <u>HTML</u>
    <i>Hello</i>
    <em>Study Hard</em>
    <del>500RS</del>
    <s>600rs</s>
    <ins>world</ins>
    <q>he says I will go"</q>
</body>

</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <ol title="square"></ol>
    <h2>SKILLS</h2>
    <li>HTML</li>
    <li>CSS</li>
    <li>javascript</li>
</ol>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>table</title>
    <link rel="stylesheet" href="table.css">
</head>
<body>
    <div class="heading">
        <h1>TABLE</h1>

    </div>

    <div class="table-container">
        <div class="table">
            
            <table border ="2px solid black">
                <tr>
                    <th colspan="2">NAME</th>
                    <th>RollNo.</th>
            <th rowspan="2">Marks</th>
        </tr>

        <tr>

          <td>NANDU</td>  
          <td>32</td>
        </tr>
        <tr>
            <td>CHANDU</td>
            <td>33</td>
        </tr>
        <tr>
            <td>ROHIT</td>
            <td>34</td>
        </tr>
    </table></div>
    </div>
    
</body>
</html>
<!DOCTYPE html>
<html lang="en">
   <head>
      <title>my first document of list html</title>
      </head>
      <body>
        <ol type="i"
            <li>html</li>
            <li>CSS</li>
            <li>javascript</li>
        </ol>
          <ol start="45"
             <li>html</li>
             <li>css</li>
             <li>javascript</li>
      </body>
      </html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Text formatting</title>
</head>
<body>
    <blockquote>This is K25DR section of html class
        Today we are learning text formatting
     </blockquote>

     He says<q>Hello world</q>
     <cite>Every action has equal and opposite reqaction.</cite>
     <p><i>Every action has equal and opposite reaction.</i></p>
     <dfn>HTML stands for hyper text markup language</dfn>
     <strong>this tag used to bold data</strong>
     <ins>this tag is used to inserts the marks text</ins>
     <abbr title="hyper text markup language">HTML</abbr><br>
     <em>this tag is used to convert into italics</em>
     <del>this tag is used to delete texts</del>
     <small>this tag is used to convert into small size</small>
     
     <mark>this tag is used to highlight the data</mark>
     
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>form Validation</title>
    <script>
        // JavaScript code for form validation can be added here
        function validateForm() {
            // Example validation logic
            let name = document.myform.username.value;
            let email = document.myform.email.value;
            if (name === "" || email === "") {
                alert("All fields must be filled out");
                return false;
            }
            let pattern = /^[^ ]+@[^ ]+\.[a-z]{2,3}$/;
            if (!email.match(pattern)) {
                alert("Please enter a valid email address");
                return false;
            }
            return true;
        }
    </script>
</head>
<body>
    <form name="myform"  onsubmit="return validateForm()">
        <h2>Form Validation Example</h2>
        <label for="username">Username:</label><br>
        <input type="text" id="username" name="username" required><br><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>
        <input type="submit" value="Submit">
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
   <style>
    #box {
    width: 150px;
    height: 200px;
    background-color: rgb(105, 178, 184);
    border: 2px solid black;
    }
   </style>
   <script>
    function box1() {
    document.getElementById("box").style.color = "red";
document.getElementById("box").style.backgroundColor = "lightgreen";
    }
    function box2() {
    document.getElementById("box").style.color = "black";  
    document.getElementById("box").style.backgroundColor = "rgb(16, 143, 152)";  
    }
    function display(){
        document.getElementById("btn").innerHTML = "DOUBLE CLICKED";

    }
   </script>
<body>
    
    <div id="box" onmouseover="box1()"> 
    <p><h2>BOX</h2></p>
    </div>
    <div id="box" onmouseout="box2()">
    <p><h2>BOX</h2></p>
    </div>
<button id = "btn" ondblclick="display()">CLICK ME</button>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>Mouse Events in HTML</title>
    <script>
        function singleClick() {
            document.getElementById("mouse-msg").innerHTML = "Single Click Detected";
        }
        function doubleClick() {
            document.getElementById("mouse-msg").innerHTML = "Double Click Detected";
        }
        function mouseOver() {
            document.getElementById("mouse-msg").innerHTML = "Mouse Over Element!";
        }
        function mouseOut() {
            document.getElementById("mouse-msg").innerHTML = "Mouse out Element!";
        }
        function mouseMove() {
            document.getElementById("mouse-msg").innerHTML = "Mouse move event triggered!";
        }
    </script>
</head>
<body>
    <h2>Mouse Based Event</h2>
    <div style= "width: 300px; height: 200px; background-color: #1b9abd; border: 2px solid black;"
    onclick="singleClick()"
    ondblclick="doubleClick()"
    onmouseover="mouseOver()"
    onmouseout="mouseOut()"
    onmousemove="mouseMove()">
    <p><h4>Move / Click Inside This Box</h4></p>
    </div>
    <p id="mouse-msg" style="color: blue; font-weight: bold;"></p>

</body>
</html>
