<html>
  <head>
    <script>
      function visOverraskelse(){
        document.getElementById("overraskelse").style.display = "inline";
      }
      function navn() {
        var person = prompt("Legg inn navnet ditt");
        if (person != null) {
          document.getElementById("demo").innerHTML =
          alert("God jul og godt nyttår til deg også " + person + ".");
        }
      }
    </script>
  </head>
  <style>
      body {
  background-color: #ff1818;
  text-align: center;
}
h1 {
  color:white;
  background-color:green;
  font-size:72px;
}
h2 {
  color:white;
}
p {
  color:white;
}
button {
  background-color: green; 
  color: white;
  padding: 6px 10px;
  text-align: center;
  text-decoration: white;
  display: inline-block;
  font-size: 14px;
}
  </style>
  <body>
  </style>
    <h1>Julekort</h1>
    <h2>Til Lasse og Micha</h2>
    <img src="juletre.png" alt="bilde av juletre" width="300">
    <p>God jul og godt nyttår Micha og Lasse!</p>
    <audio controls>
      <source src="Innspilling (5).m4a">
   </audio>
   <p>Trykk <button onclick="visOverraskelse();navn()">her</button> for en overraskelse!</p>
   <div id="overraskelse" style="display:none">
        <img src="sngirru-m.gif" alt="gif av julenisse" width="300">
        <div>
        <button onclick="location.reload()">Start siden på nytt</button>
        </div>
   </div>
  </body>
</html>
