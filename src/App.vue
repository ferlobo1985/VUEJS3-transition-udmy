<template>
  <app-header></app-header>
        <div class="container">
            <!-- <compTransitionsOne></compTransitionsOne> -->
            <comp-transitions-three></comp-transitions-three>
        </div>
    <app-footer></app-footer>
</template>

<script>
  // import compTransitionsOne from './components/Transitions/one';
  // import compTransitionsTwo from './components/Transitions/two.vue';
    import compTransitionsThree from './components/Transitions/three.vue';

  export default{
    components:{
      compTransitionsThree
    }
  }
</script>
