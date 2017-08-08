## Welcome to the Down Comparison Calculator

Have you ever wondered how a  jacket with 150g of 750 fill power down compares with a jacket of 190g of 650 fill power down? 

This site allows you to enter the fill weight and fill power of any down filled item to calculate its total loft and therefore its warmth. Using this will allow you to compare down filled items with differnt fill powers and/or fill weights.

<form id="frm1" action="/action_page.php">
  First name: <input type="text" name="fname" value="Test"><br>
</form> 

<button onclick="myFunction()">Try it</button>

<p id="demo"></p>

<script>
function myFunction() {
    var x = document.getElementById("frm1");
    var text = "";
    var i;
    for (i = 0; i < x.length ;i++) {
        text += x.elements[i].value + "<br>";
    }
    document.getElementById("demo").innerHTML = text;
}
</script>

Testing
