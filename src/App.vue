<template>
    <Header />
    <Slider />
</template>

<script>
import "@/styles/general.css";
import Header from '@/elements/Header'
import Slider from '@/elements/Slider'

export default {
  name: "App",
  components: {
    Header,
    Slider
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700;900&display=swap');
html,
body {
  box-sizing: border-box;
  font-size: 62.5%;
  font-family:"Roboto", sans-serif;
  background-color: #ebebeb;
}
</style>
