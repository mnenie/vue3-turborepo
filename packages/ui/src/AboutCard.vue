<template>
  <div class="card">
    <slot />
  </div>
</template>


<style scoped>
.card{
  padding: 10px 30px;
  box-shadow: 0px 5px 10px 2px rgba(34, 60, 80, 0.2);
  display: flex;
  flex-direction: column;
  gap: 5px;
}
</style>