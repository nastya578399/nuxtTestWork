<template>
  <div class="block">
    <add-product-component />
    
    <list-products-component />
    
  </div>
</template>

<script>


export default {
  data() {
    return {
      
    }
  }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@400;600&display=swap');

body{
  background: #E5E5E5;
}

.block{
  display: flex;
}

@media screen and (max-width: 480px) {
  .block {
    display: block;
  }
}
</style>