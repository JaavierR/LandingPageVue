<script setup>
import Cover from './components/Cover.vue';
import Manifesto from './components/Manifesto.vue';
import Register from './components/Register.vue';
</script>

<template>
  <header>
    <Cover />
  </header>
  <body>
    <Manifesto />

    <Register />
  </body>
</template>

<style>
* {
        margin: 0;
        padding: 0;
        border: 0;
        outline: 0;
        font-size: 100%;
        vertical-align: baseline;
        background: transparent;
    }
</style>