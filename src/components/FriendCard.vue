<template>
    <div class="card-container">
        <div class="card">
            <h2>Ronan Orgo</h2>
            <p>The best of the best</p>
        </div>
    </div>
</template>

<script>
export default {
      name: "FriendCard",

}
</script>

<style scoped>
* {
  box-sizing: border-box;
}

html {
  font-family: 'Jost', sans-serif;
}

body {
  margin: 0;
}

.card-container .card{
    width: 40%;
    margin:20px auto;
    background: rgb(255, 254, 254);
    box-shadow: 0px 0px 5px 2px #ccc;
    padding: 10px 20px;
    border-radius: 4px;
    margin-top: 20px;
}
</style>
