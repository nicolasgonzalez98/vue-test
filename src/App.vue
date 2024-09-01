<script setup>
  const name ="nico"
  const styleColor="color:green;"

//metodo

const handleClick = (msg) => {
  console.log(msg)
}

//   const arrayFrutas = [
//     {
//         name: "Manzana",
//         price: "$1.00",
//         description: "Una manzana",
//         stock: 0
//     },
//     {
//         name: "Pera",
//         price: "$2.00",
//         description: "Una pera",
//         stock: 10
//     },
//     {
//         name: "Naranja",
//         price: "$3.00",
//         description: "Una naranja",
//         stock: 20
//     },
// ];

// const objFruta = {
//         name: "Manzana",
//         price: "$1.00",
//         description: "Una manzana roja",
//         stock: 30
//     }

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
