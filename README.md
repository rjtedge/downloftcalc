## Welcome to the Down Comparison Calculator

Have you ever wondered how a  jacket with 150g of 750 fill power down compares with a jacket of 190g of 650 fill power down? 

This site allows you to enter the fill weight and fill power of any down filled item to calculate its total loft and therefore its warmth. Using this will allow you to compare down filled items with differnt fill powers and/or fill weights.

<form id="frm1" action="/action_page.php">
  Fill Power: <input type="number" id="fpower" oninput="myFunction()" value="800"><br>
  Fill Weight: <input type="text" id="fweight" oninput="myFunction()" value="150"><br>
</form> 


### Total Loft 
<p id="demo"></p>cubic centermeeters of loft

### Weight (in grams) of down required for different loft powers to achieve the same total loft (and therefore warmth)
<p id="f500"></p>grams of 500 fill power down <br>
<p id="f550"></p>grams of 550 fill power down <br>
<p id="f600"></p>grams of 600 fill power down <br>
<p id="f650"></p>grams of 650 fill power down <br>
<p id="f700"></p>grams of 700 fill power down <br>
<p id="f750"></p>grams of 750 fill power down <br>
<p id="f800"></p>grams of 800 fill power down <br>
<p id="f850"></p>grams of 850 fill power down <br>
<p id="f900"></p>grams of 900 fill power down <br>

<script>
function myFunction() {
    var fp = document.getElementById("fpower").value;
    var fw = document.getElementById("fweight").value;
    var oztog = 28.3495
    var totalloft = (fw/(oztog/fp));
    var f500 = (totalloft*(oztog/500));
    var f550 = (totalloft*(oztog/550));
    var f600 = (totalloft*(oztog/600));
    var f650 = (totalloft*(oztog/650));
    var f700 = (totalloft*(oztog/700));
    var f750 = (totalloft*(oztog/750));
    var f800 = (totalloft*(oztog/800));
    var f850 = (totalloft*(oztog/850));
    var f900 = (totalloft*(oztog/900)); 

  document.getElementById("demo").innerHTML = Math.round(totalloft);
  document.getElementById("f500").innerHTML = Math.round(f500);
  document.getElementById("f550").innerHTML = Math.round(f550);  
  document.getElementById("f600").innerHTML = Math.round(f600);  
  document.getElementById("f650").innerHTML = Math.round(f650);
  document.getElementById("f700").innerHTML = Math.round(f700);  
  document.getElementById("f750").innerHTML = Math.round(f750);  
  document.getElementById("f800").innerHTML = Math.round(f800);  
  document.getElementById("f850").innerHTML = Math.round(f850);  
  document.getElementById("f900").innerHTML = Math.round(f900);  

}
</script>