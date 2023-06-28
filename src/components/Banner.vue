<template>
  <div id="main-banner">
    <p><strong>Make Your Burger</strong></p>
  </div>
</template>


<script >
export default {
  name: "Banner"
}

</script>



<style scoped>

  #main-banner{
    background-image: url('/public/img/burger.jpg');
    background-position: 0;
    background-size: cover;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
  }

  #main-banner{
    color: #fff;
    text-align: center;
    font-size: 60px;
    background-color: #f12525;
    padding: 20px 40px;
  }
</style>