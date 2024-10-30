<!--script----->
<script setup>

let validacao = false

</script>
<!--CSS-->
  <style>
  .ok{color: grey;}
  .falha{color: red;}

 </style>

<!--HTML-->
<template>

    <p :class="validacao ?'ok':'falha'">utilizando diretivas</p>
</template>

