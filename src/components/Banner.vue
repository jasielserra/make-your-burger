<template>
  <div id="main-burger">
    <h1>Make Your Burger</h1>
  </div>
</template>

<script>
export default {
  name: "Banner"
}
</script>

<style scoped>

  #main-burger {
    background-image: url('/home/jasiel/PycharmProjects/make_your_burger/public/img/burger.jpg');
    background-position: 0 -250px;
    background-size: cover;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
  }

  #main-burger h1 {
    color: #FFF;
    text-align: center;
    font-size: 60px;
    background-color: #222;
    padding: 20px 40px;
  }


</style>