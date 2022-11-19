<template>
  <div id="app">
    
    <router-view/>
  </div>
</template>

<style>
 /* @font-face {
  font-family: Thasadith-Regular;
  src: url("{{ url_for('static', filename='Thasadith-Regular.ttf') }}");
  font-weight: normal;
}
@font-face {
  font-family: Thasadith-Bold;
  src: url("{{ url_for('static', filename='Thasadith-Bold.ttf') }}");
  font-weight: bold;
}
@font-face {
  font-family: Thasadith-BoldItalic;
  src: url("{{ url_for('static', filename='Thasadith-BoldItalic.ttf') }}");
  font-weight: bold;
}
@font-face {
  font-family: Thasadith-Italic;
  src: url("filename='Thasadith-Italic.ttf'");
  font-weight: bold;
} */
@import url('https://fonts.googleapis.com/css2?family=Thasadith:ital,wght@0,400;0,700;1,400;1,700&display=swap');
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50; */
  margin-top: 60px;
  font-family: 'Thasadith', sans-serif;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}

</style>
