<!--script--->
<script setup>

let texto= '<p style=color:red> apredendo a diretiva v-html </p>';
</script>
<!--HTML---->
<template>

    <div v-html="texto"></div>
    {{ texto }}
</template>