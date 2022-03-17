<template>
    <div id="about-us">
      <div id="todo-card">
         <div class="container">
    
<div class="alert alert-primary" role="alert">
    <h1>{{ msg6 }}</h1>
</div>
    <!-- Content here -->
     <br/>
    <h2 style="background-color:Tomato;">Primary School</h2>
    <h2><b>Primary Education</b></h2>
    <p>Sto. Rosario Elementary School, Angeles Pampanga
    </p>
    <p>June 2008 - June 2014 </p>
    <br/>
    <h2 style="background-color:Tomato;">Primary School</h2>
    <h2><b>Secondary Education (JHS-SHS)</b></h2>
    <p>Holy Angel University, Angeles Pampanga
    </p>
    <p>June 2015 - June 2020</p>
    <br/>
    <h2 style="background-color:Tomato;">Primary School</h2>
    <h2><b>Tertiary Education</b></h2>
    <p>Holy Angel University, Angeles  Pampanga</p>
    <p>August 2021 - August 2024</p>
    <br/>
    
    <p>Bachelor of Science in Information Technology Major in WebDev</p>
    <p>Dean's List - S.Y 2021-2022</p>
    <h2 style="background-color:Tomato;">Primary School</h2>




</div>
  </div>
  </div>

</template>

<script>
 
  export default {
    name: 'about-us',
    data () { 
      return {
        msg6: 'This is the Education Component'
      }
    }
  }
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
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
  color: #42b983;
}
 
.title h1 {
  color: #42b983;
}
 
</style>