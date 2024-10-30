<!--script------>
<script setup>

 function messagem(){

    alert ('Trabalhando com eventos de  clique')
 }
</script>
<!--HTML------>
<template>
    <button @click="messagem()" >clique aki</button>
</template>
