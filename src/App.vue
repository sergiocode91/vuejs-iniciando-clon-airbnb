<template>
  <div id="app">
    <HeaderComponent></HeaderComponent>
    <div class="container">
      <TagsComponent></TagsComponent>
      <WorldComponent></WorldComponent>
      <BestComponent></BestComponent>
    </div>
  </div>
</template>

<script>
  import HeaderComponent from './components/HeaderComponent.vue'
  import TagsComponent from './components/TagsComponent.vue'
  import WorldComponent from './components/WorldComponent.vue'
  import BestComponent from './components/BestComponent.vue'

  export default {
    name: 'App',
    components: {
      HeaderComponent,
      TagsComponent,
      WorldComponent,
      BestComponent
    }
  }
  </script>

<style>
  @import url(./assets/css/style.css);
</style>
