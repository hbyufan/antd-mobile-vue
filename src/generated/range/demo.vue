<template>
  <div>
    
  </div>
</template>
<script lang="ts">
  import DemoWrapper from '@/components/demo-wrapper.vue';
  
  import Vue from 'vue';
  import Component from 'vue-class-component';

  @Component({
    name: 'Demo',
    components: { DemoWrapper}
  })
  export default class Demo extends Vue {
  }
</script>
