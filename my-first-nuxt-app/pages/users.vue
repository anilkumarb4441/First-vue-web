<template>
    <div>
        
    <!-- <h1> This is Users Page </h1> -->
    <input type="text" />
    <button @click="onLoadId" > Load User </button>
    <nuxt-child />
    </div>
</template>

<script>

export default {
    
    data() {
      return {
          userId:' ',
      }  

    },
    methods:{
        onLoadId(){
          this.$router.push('/users/' + this.userId);
        },
    },
    layout: 'users',
}
</script>
