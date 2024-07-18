<script setup>
import { ref } from 'vue';
const count = ref(0);
</script>

<template>

  <main>

    <div class="counter">

      <h1>counter</h1>

      <span> <button @click="count++" class="add">+
        </button> </span> <span>
        <h4 class="count">{{ count }}</h4>
      </span> <span><button @click="count--" class="minus">-</button></span>

    </div>

  </main>

</template>

<style scoped>
h4,
button {
  display: inline-block;
}

body {
  width: 100vw;
  height: 100vh;
  background-color: aliceblue;
  display: flex;
  align-items: center;
  justify-content: center;
}

div {
  text-align: center;

}
</style>
