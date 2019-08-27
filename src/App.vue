<template>
  <div>
    <form-helper> 
        <div slot ="form-header">
          <h3>Pension Form</h3>
          <hr>
          <p>Fill the form as required</p>
       </div> 

      <div slot="form-field">
        <input type="text" placeholder="name" required/><br>
        <input type ="password" placeholder = "password" required/>
      </div>

    <div slot="form-controls">
      <button v-on:click="handleSubmit">Submit</button>
    </div>
    
    </form-helper>
  </div>
</template>




<script>
import formHelper from './components/formHelper.vue' 
export default{
  components:{
    'form-helper':formHelper
  },
  data(){
    return{
      title:"I like VueJs"

    }
  },
  methods:{

  }
  }

</script>

<style lang="scss">


</style>
