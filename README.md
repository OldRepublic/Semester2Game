# DustBunn
Ashley Proctor


<!DOCTYPE html>
<html>
<img id="canvas" width="600" height="600" src="https://goo.gl/GAWnPK" alt="The canvas" style="display: none;">
<body>
	<style>
.p {
    display: block;
    margin-left: auto;
    margin-right: auto;
}
canvas {
    display: block;
    margin-left: auto;
    margin-right: auto;
}
</style>


<p>Canvas:</p>
<canvas id="myCanvas" width="600" height="600" style="border:1px solid #d3d3d3;">
Your browser does not support the HTML5 canvas tag.
</canvas>

<script>
window.onload = function() {
    var c = document.getElementById("myCanvas");
    var ctx = c.getContext("2d");
    var img = document.getElementById("canvas");
    ctx.drawImage(img, 0, 0);
}
</script>

<p>TEMP</p>

</body>
</html>
