<script setup>
import LikeSad from "../src/components/likeSad.vue";
</script>
<template>
<div class="row">
  <div v-for="n in 6" :key="n" class="col-4">
    <div class="card bg-dark" style="width: 18rem ">
      <img src="./assets/images.jfif" class="card-img-top" alt="..." />
      <div class="card-body">
        <h5 class="card-title">shirokane</h5>
        <p class="card-text" >
          kei shirokane
        </p>
      </div>
    </div>
    <LikeSad></LikeSad>
  </div>
</div>
</template>
