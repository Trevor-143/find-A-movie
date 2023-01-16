<template>
  <header>
    <router-link to=""><h1><span>Vue</span>Movies</h1></router-link>
  </header>  
  <main>
    <router-view/>
  </main>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800;900&family=Sofia+Sans+Condensed:wght@100;200;300;400;500;600;700;800;900&display=swap');

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: 'poppins', 'sans-serif';
}
body {
  background-color: #d6d6d6;

}
a {
  text-decoration: none;
}
header {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 10px 16px;
  background-color: rgb(0, 0, 0);
  box-shadow: 0px 0px 6px rgba(0 0 0 0.2);
}
header h1 {
  color: #ffffff;
  font-size: 28px;
}
header h1 span {
  color: #ff0000;
}
</style>
