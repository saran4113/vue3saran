<template>
  <h1>{{message}}</h1>
  <HelloWorld />
</template>

<script>
import HelloWorld from "~/components/HelloWorld";
export default {
  components:{
    HelloWorld
  },
  data(){
    return {
      message: '헬로우2'
    }
  }
}
</script>
