<h1>Primeiro projeto</h1>
<h2> Explicacão de coisas e mais coisas nessa área</h2>

$brandColor: darkorchid;

body {
  font-family: system-ui, sans-serif;
  background: linear-gradient(to bottom,
    $brandColor,
    darken($brandColor, 15%)
  );
  color: white;
  height: 100vh;
  margin: 0;
  display: grid;
  place-items: line;
}

document.getElementsByTagName("h1")[0].style.fontSize = "6vw";
