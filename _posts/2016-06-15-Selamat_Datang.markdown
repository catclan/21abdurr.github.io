---
layout: post
---



<html>
<body>

<div id="result"></div>

<script>
// Check browser support
if (typeof(Storage) !== "undefined") {
    // Store
    localStorage.setItem("Westlife", "Mylove");
    // Retrieve
    document.getElementById("result").innerHTML = localStorage.getItem("lastname");
} else {
    document.getElementById("result").innerHTML = "Sorry, your browser does not support Web Storage...";
}
</script>


<p>Westlife - My love<br>
<audio controls="controls">
  <source src="/multimedia/My love - Weslife.ogg" type="audio/ogg" />
  <!--<source src="/multimedia/Ayu Ting Ting - Sambalado.ogg" type="audio/ogg"/>-->
Your browser does not support the audio element.
</audio> 
</p>
</body>
</html>

