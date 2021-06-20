<template>
  <h1>{{ msg }}</h1>
  <img src="GROWPOTBOT-L1.0b7c3f71.png" />
  <!--
  <button @click="count++">count is: {{ count }}</button>
  <p>Edit <code>components/HelloWorld.vue</code> to test hot module replacement.</p>
  -->
</template>

<script>
export default {
  name: 'GrowPotBot',
  props: {
    msg: String
  },
  data() {
    return {
      count: 0
    }
  }
}
</script>
