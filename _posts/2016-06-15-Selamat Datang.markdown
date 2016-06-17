---
layout: post
---



<html manifest="cache-manifest.manifest">
<body>



<div>
	
	<h3> coba dengarkan seksama musik dibawah ini</h3>
<br>pastinya menggunakan format .Ogg :D <br>


<p>Westlife - My love<br> tanpa fate in dan Fat out <br>
<audio controls="controls">
  <source src="/multimedia/My love - Weslife.ogg" type="audio/ogg" />
  Your browser does not support the audio element.
</audio> 
</p>
<p>Ayu tingting - sambal lado<br>dengan fate in dan fate out<br>
<audio controls="controls">
   <source src="/multimedia/Ayu Ting Ting - Sambalado.ogg" type="audio/ogg"/>
Your browser does not support the audio element.
</audio>


</div>
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

 </body>
</html>