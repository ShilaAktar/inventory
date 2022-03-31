<template>
  <div>
      
   
         
  </div>
</template>

<script type="text/javascript">
export default{
    created(){
      if (!User.loggedIn()) {
        this.$router.push({name: '/'})
      }
    }
}

</script>

<style text="text/css">
</style>


