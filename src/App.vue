<template>
  <app-header></app-header>
        <div class="container">
            <!-- <compTransitionsOne></compTransitionsOne> -->
            <comp-transitions-two></comp-transitions-two>
        </div>
    <app-footer></app-footer>
</template>

<script>
  // import compTransitionsOne from './components/Transitions/one';
  import compTransitionsTwo from './components/Transitions/two.vue';

  export default{
    components:{
      compTransitionsTwo
    }
  }
</script>
