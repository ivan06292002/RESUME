<template>
      <div id="todo-card">
         <div class="container">
    
<div class="alert alert-info" role="alert">
    <h1>{{ msg2 }}</h1>
</div>
    <br/>
    <h2 style="background-color:Tomato;">Primary School</h2>
    <h2><b>Objective</b></h2>
    <p>To gain confidence and fame using my potential in the field of “Web Development”, and express my innovative creative skills for self and company growth.</p>
    <h2 style="background-color:Tomato;">Primary School</h2>
    <br/>
    <h2><b>Name</b></h2>
    <p>Carl Ivan P. Dayrit</p>
    <h2 style="background-color:Tomato;">Primary School</h2>
    <br/>
    <h2><b>Course</b></h2>
    <p>BS IT</p>
    <h2 style="background-color:Tomato;">Primary School</h2>
    <br/>
    <h2><b>Specialization</b></h2>
    <p>Web Development</p>
    <br/>
    <h2 style="background-color:Tomato;">Primary School</h2>

</div>
  </div>
  
</template>

<script>
 
  export default {
    name: 'todo-card',
    data () {
      return {
        
        msg2: 'This is the Profile Component'
      }
    }
  }
</script>