# hello-world
<!DOCTYPE HTML>
<html>
<body>
<H1>JavaScript program to find A^B</H1>
<p>Click on button to get the prompt.</p>

<button onclick="myFunction()">Click me</button>

<p id="demo"></p>

<script>
function myFunction(){
	var x = prompt("please input the value of A", "0");
	var y = prompt("please input the value of B", "0");
	var z = Math.pow(x,y);
	document.getElementById("demo").innerHTML = z;
}

</script>

</body>
</html>
