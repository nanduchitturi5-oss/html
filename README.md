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
