<template>
<div class="hello">
  <nav class="navbar navbar-expand-lg navbar-light bg-white">
    <a class="navbar-brand">
      <router-link to="/">kollo cash</router-link>
    </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse " id="navbarSupportedContent">
    
     
    </div>
  </nav>
</div>
</template>

<script>
export default {
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style scoped>
ul {
  margin: 0 auto;
  color: black;
  font-weight: bolder;
  padding: 2rem;
  font-size: 1.5em;
}

nav{
  background-color: #E5E5E5 !important;
}

button{
  
  padding-right: 3em;
    padding-left: 3em;
}

button:hover{
  
    background-color: #640064 !important;
   
}
#nav a.router-link-exact-active {
    color: #640064 !important;
}

</style>