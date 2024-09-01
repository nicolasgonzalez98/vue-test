<script setup>
  const name ="nico"
  const styleColor="color:green;"

//metodo

const increment = () => {
  console.log("incremento")
}



</script>

<template>
  
  
  <button @click.right.prevent="handleClick('hola')">Activame right</button>

  <button @click="handleClick('hola amor')">Activame</button>
</template>

<style scoped>
h1{
  color: red;
}
</style>
