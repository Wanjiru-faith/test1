<template>
 <div>

    <form>
    <h1>hyhyhyhy</h1>
      <div id="form-header">
        <slot name="form-header"></slot>
      </div>

      <div id="form-field">
        <slot name="form-field"></slot>
      </div> 

      <div id="form-controls">
        <slot name="form-controls"></slot>
        </div>

       <div id="useful-links">
            <ul>
                <li><a href='#'>Link 1</a></li>
                <li><a href='#'>Link 2</a></li>
                <li><a href='#'>Link 3</a></li>
                <li><a href='#'>Link 4</a></li>
            </ul>
       </div>
      </form>
  </div>
</template>
<script>
 
export default{
  components:{
    
  },
  data(){
    return{

    }
  },
  methods:{

  }
  }

</script>

<style scoped>
h3{
    background:green;
    color: balck;
    max-height: 600px;

}
#form-field{
  display: flex;
  align-items: center;
  justify-content: center;
    display: inline;
    float: none;
    background:blue;

}
#useful-links{
    color: red;
  font-family: helvetica;
  text-decoration: none;
  text-transform: lowercase;

}
#form-controls{
    display: flex;
  align-items: center;
  justify-content: center;
 

}
#form-controls button{
    border-radius:3px;
    color:blue;
    background:red;
}


</style>