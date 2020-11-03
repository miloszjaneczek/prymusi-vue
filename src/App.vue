<template>
<div>
<input v-model="aa" placeholder="write something">
<p>Message: {{ aa }}</p>
</div>
</template>

<script>
export default {
  data(){
    return{ 
      aa: "nie"
    }
  }

}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
