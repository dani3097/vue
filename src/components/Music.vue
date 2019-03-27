<template>
<body>
  <div class="music">
    <h1>{{ msg }}</h1>
    <p>Coldplay es una banda británica de pop rock y rock alternativo formada en Londres en 1996. </p>
    <p>El grupo está integrado por Chris Martin (voz, teclado, guitarra), Jon Buckland (guitarra principal), Guy Berryman (bajo eléctrico) y Will Champion (batería, coros y otros instrumentos).</p>
    <h2>Favorite videos</h2>
    <ul>
      <li><a  href="https://www.youtube.com/watch?v=RB-RcX5DS5A"  target="_blank">
          The Scientist
        </a>
      </li>
      <li><a href="https://www.youtube.com/watch?v=BPNTC7uZYrI" target="_blank">
          Up and Up
        </a>
      </li>
      <li> <a href="https://www.youtube.com/watch?v=k4V3Mo61fJM" target="_blank">
          Fix You
        </a>
      </li>
      <li><a href="https://www.youtube.com/watch?v=1G4isv_Fylg" target="_blank">
          Paradise
        </a>
      </li>

      <br>

      <li><a href="https://www.youtube.com/watch?v=abbSfBu2Vwc" target="_blank">
          Documental Coldplay
        </a>
      </li>
    </ul>
    
  </div>
</body>
</template>

<script>
export default {
  name: "Music",
  data() {
    return {
      msg: "All about my favorite songs of Coldplay"
      
    };
  }
};
</script>

<!--  "scoped" limita el CSS aeste componente solamente -->
<style scoped>
h1{
  color: rgb(12, 16, 241);
  text-align: center;
  font-weight: normal;
}
h2 {
  color: rgb(213, 32, 219);
  text-align: center;
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #cb4ff1;
}
body {
  background-image: url("https://www.senorcool.com/system/files/styles/large/private/senorcool_rilustrart_hojas.jpg?itok=zJaZiEZr");
  background-color: rgb(173, 230, 213);
}


</style>
