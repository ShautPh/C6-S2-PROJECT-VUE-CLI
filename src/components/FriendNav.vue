<template>
      <header>
        <ul>
            <li>
                <a href="#">Home</a>
            </li>
            <li>
                <a href="#">About Us</a>
            </li>
            <li>
                <a href="#">Services</a>
            </li>
            <li>
                <a href="#">Help?</a>
            </li>
        </ul>
      </header>
</template>

<script>
export default {
    name: "FriendNav",
    data(){
        return{
        }
    }
}
</script>

<style scoped>
header {
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
  margin: auto;
  padding: 1rem;
  background-color: #e91437;
  color: white;
  text-align: center;
  width: 100%;
  max-width: 100%;
  position: sticky; 
  top: 0;
  z-index: 1;

}

#app ul {
  margin: 0;
  padding: 0;
  list-style: none;
  display: flex;
}
#app ul li{
  margin: 10px 16px;
  padding: 0;
}

#app ul li a{
  text-decoration: none;
  text-transform: uppercase;
  color: #ffff;
  font-weight: 800;
}


</style>
