<script>


export default{
    name: 'projectView',
    data: () =>({
        title: 'project',
    }),
};
</script>

<template>
<div class="project">
  <h1>{{title}}</h1>
</div>
</template>

<style>
@media (min-width: 1024px ;){
  .test{
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}</style>