<html>

    <body>
    <button onclick="Decrease()" value="Decrease">-</button>
    <p type="referinta"> 0 </p>
    <button onclick="Increase()" value="Increase">+</button>
    </body>
<script>
     var Count=0;

function Increase()
{
   Count++;               
    document.getElementById("referinta").innerHTML=Count;
}

function Decrease()
{
   Count--;               
    document.getElementById("referinta").innerHTML=Count;
}
    </script>

</html>
