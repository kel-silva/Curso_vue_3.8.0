<!--script---->

<script setup>

//exibir variavel
let exibir = true;
let media = 2;


</script>

<!--HTML------>
<template>

    
    <p v-if="media>= 7">Aproivado(a)</p>
    <p v-else-if="media >=5">em EXAme</p>
    <p v-else>Reprovado</p>
</template>
