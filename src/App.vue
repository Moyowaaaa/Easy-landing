<template>
  <div id="app">
    <!-- <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav> -->
    <router-view />
  </div>
</template>

<style>
#app {
 
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

}

@font-face{
  font-family: 'avenir-black';
  src: local('avenir-black'),
  url('./fonts/Avenir-Black.otf') format('opentype');


}

@font-face{
  font-family: 'avenir-heavy';
  src: local('avenir-heavy'),
  url('./fonts/Avenir-Heavy.otf') format('opentype');

}
@font-face{
  font-family: 'avenir-md';
  src: local('avenir-md'),
  url('./fonts/Avenir-Medium.otf') format('opentype');

}

@font-face{
  font-family: 'avenir-o';
  src: local('avenir-oblique'),
  url('./fonts/Avenir-Ob.otf') format('opentype');

}

@font-face{
  font-family: 'avenir-light';
  src: local('avenir-light'),
  url('./fonts/Avenir-Light.otf') format('opentype');
   font-weight: 400;
}

@font-face{
    font-family: "gotham-black";
    src: local('gotham-black'),
    url('./fonts/Gotham-Black.otf') format('opentype');
}

@font-face{
    font-family: "gotham-light";
    src: local('gotham-light'),
    url('./fonts/GothamLight.otf') format('opentype');
}


@font-face{
    font-family: "gotham-md";
    src: local('gotham-md'),
    url('./fonts/GothamMedium.otf') format('opentype');
   
}
@font-face{
    font-family: "gotham-bold";
    src: local('gotham-bold'),
    url('./fonts/GothamBold.otf') format('opentype');
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
::-webkit-scrollbar {
  width: 2px;
  

}
::-webkit-scrollbar-track {
  background: #222222;
}
::-webkit-scrollbar-thumb {
  background: #F6FF82;
}

</style>
