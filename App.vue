<template>
  <div class="container">
      Hello {{bundler}}
  </div>
</template>

<script>
import Vue from "vue";
import { Slide } from 'vue-burger-menu';

export default{
  name: "App",
  components: {
    HelloWorld
  },
  data: function(){
    return {
      bundler: "Parcel"
    };
  }
};
</script>

<style lang="scss" scoped>
.container {
  color: green;
}
</style>
