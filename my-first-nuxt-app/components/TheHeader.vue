<template>
  <header class="header">
    <ul class="nav_item">
      <li>
        <nuxt-link to="/"> Home </nuxt-link>
      </li>
      <li>
        <nuxt-link to="/users"> Users </nuxt-link>
      </li>
    </ul>
  </header>
</template>

<style scoped>
.header{
    width:100%;
    height: 60px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: rgb(202, 199, 199);
}

.nav_item{
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
   justify-content: space-around;
   align-items: center;
   width:80%;
   font-size: 20px;
}

.nav_item a{
    text-decoration: none;
    color:black;
}

.nav_item a:hover,
.nav_item a:active{
    color:#fff;
  
}
</style>