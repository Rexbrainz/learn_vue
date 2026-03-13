<script lang="ts">
  import HeadingComponent from './components/HeadingComponent.vue';
  
  export default {
    components: {
      HeadingComponent,
    }
  }
</script>

<template>
    <section class="wrapper">
        <HeadingComponent />
        <span class="heading"> This is span element in App.vue component</span>
    </section>
</template>
