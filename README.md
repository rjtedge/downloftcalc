## Welcome to the Down Comparison Calculator

Have you ever wondered how a  jacket with 150g of 750 fill power down compares with a jacket of 190g of 650 fill power down? 

This site allows you to enter the fill weight and fill power of any down filled item to calculate its total loft and therefore its warmth. Using this will allow you to compare down filled items with differnt fill powers and/or fill weights.

<form id="frm1" action="/action_page.php">
  Fill Power: <input type="number" name="fpower" value="800"><br>
  Fill Weight: <input type="text" name="fweight" value="150"><br>
</form> 

<button onclick="myFunction()">Compare loft</button>

<p id="demo"></p>

<script>
function myFunction() {
    var fp = document.getElementsByName("fpower")[0].value;
    var fweight = document.getElementsByNameById("fweight")[0].value;
    alert(fp);
    document.getElementById("demo").innerHTML = fp.value;
}
</script>



End test