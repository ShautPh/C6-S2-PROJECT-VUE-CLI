<template>
<div class="container">
            <form >
                <div class="input-group">
                    <input type="text" required placeholder="First name" v-model="firstName">
                    <input type="text" required placeholder="Last name" v-model="lastName">
                    <input type="text" required placeholder="Comment" v-model="comment">
                <Button/>
                </div>
            </form>
        </div>
</template>

<script>
import ButtonView from "./ButtonView.vue"
export default {
    name: "FriendForm",
    components: {
        "Button": ButtonView
    },
    
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
.container{
    background: rgb(255, 254, 254);
    width: 40%;
    margin:20px auto;
    box-shadow: 0px 0px 5px 2px #ccc;
    padding: 10px 20px;
    border-radius: 4px;
}

.container .input-group{
    margin: 10px;
    padding: 20px 0;
}
.container .input-group input{
    padding: 12px 8px;
    font-size: 18px;
    border: 2px solid #ccc;
    margin-bottom: 20px;
    border-radius: 6px;
    outline: none;
    width: 100%;
}
.container input:focus, select:focus{
    box-shadow: 0px 0px 8px 3px #e91437;
    transition: ease .8s;
}
.search-food {
    width: 90%;
    box-shadow: 0px 0px 16px 2px #ccc;
    box-sizing: border-box;
    text-align: center;
    margin: auto;
    padding: 20px;
    border-radius: 6px;

}
.search-food input{
    padding: 12px 8px;
    font-size: 18px;
    border: 4px solid rgb(7, 167, 172);
    border-radius: 4px;
    width: 100%;
    outline: none;
    box-sizing: border-box;
}

.search-food i{
    background: rgb(7, 167, 172);
    width: 40px;
    height: 40px;
    position: relative;
    float: right;
    top: -46px;
    right: 8px;
    color: white;
    font-size: 24px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 4px;
    cursor: pointer;
    /* opacity: 0; */
    display: none;
}

.search-food input:focus .search-food i{
    display: block;
}

</style>
