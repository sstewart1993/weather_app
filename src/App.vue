<template>
  <div id="app">
    <main>
      <div class="search-box">
        <input type="text" class="search-bar" placeholder="Search..." />
      </div> 
    </main>
  </div>
</template>

<script>


export default {
  name: 'App',
  data(){
    return{
    api_key: 'd405f383b40b79aff1da4558167dc800'
    }
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body{
  font-family: 'montserrat', sans-serif;
}

#app{
  background-image: url('./assets/cold.jpg');
  background-repeat: no-repeat;
  background-size: contain;
  transition: 0.4s;
}

main{
  height: 100vh;
  padding:25px;
  background-image: linear-gradient(to bottom, rgba(0,0,0,0.25), rgba(0,0,0,0.75));
}

</style>
