<template>
    <section id="app">
      <Navbar/>
      <Form/>
      <Card/>
      <Card/>
      <Card/>
    </section> 
</template>

<script>
import FriendNav from "./components/FriendNav.vue";
import FriendForm from "./components/FriendForm.vue";
import FriendCard from "./components/FriendCard.vue";

export default {
  name: "App",
  components: {
    "Navbar": FriendNav,
    "Form": FriendForm,
    "Card": FriendCard,

  }
}
</script>

<style>
* {
  box-sizing: border-box;
}

html {
  font-family: 'Jost', sans-serif;
}

body {
  margin: 0;
}



</style>
