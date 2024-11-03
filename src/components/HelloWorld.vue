<template>
  <h2>my name is: {{name}} myfamilyis : {{family}}</h2>
  <hr/>
  <p></p>
  <button @click="textP">click</button>
</template>

<script>
export default {
  name: 'HelloWorld',
  props:{
    id:Number,
    name:String,
    family:String,
    text:String,
  },
  methods:{
    textP(){
      //this.$emit('getText',this.id)
      return 0
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
