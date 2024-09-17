<script>
export default {
  data() {
    return {
    };
  }

}
</script>

<template>
  <main>
    <div class="content-box">
      <div class="container">
        <p>
          Content Goes Here
        </p>
      </div>
    </div>

    <div class="icon-box">
      <div class="container">
        <span>
          <img class="icon" src="../assets/vue-dc-comics-1/img/buy-comics-digital-comics.png" alt="Digital Comics">
          <p>DIGITAL COMICS</p>
        </span>
        <span>
          <img class="icon" src="../assets/vue-dc-comics-1/img/buy-comics-digital-comics.png" alt="Digital Comics">
          <p>DC MERCHANDISE</p>
        </span>
        <span>
          <img class="icon" src="../assets/vue-dc-comics-1/img/buy-comics-digital-comics.png" alt="Digital Comics">
          <p>SUBSCRIPTION</p>
        </span>
        <span>
          <img class="icon" src="../assets/vue-dc-comics-1/img/buy-comics-digital-comics.png" alt="Digital Comics">
          <p>COMIC SHOP LOCATOR</p>
        </span>
        <span>
          <img class="icon" src="../assets/vue-dc-comics-1/img/buy-comics-digital-comics.png" alt="Digital Comics">
          <p>DC POWER VISA</p>
        </span>

      </div>
    </div>
    
  </main>
</template>

<style scoped>

main > .content-box {
  height: 150px;
  background-color: #1C1C1C;
  color: white;
  padding: 25px 0;
  display: flex;
  align-items: center;
}

.content-box > .container > p {
  font-size: 25px;
}

main > .icon-box{
  height: 150px;
  display: flex;
  justify-content: space-between;
  background-color: #097CEB;
  color: white;
  padding: 25px 0;
}

.icon-box > .container{
  display: flex;
  justify-content: space-between;
}

.container > span {
  display: flex;
  align-items: center;
  margin: 0 25px;
}

.container > span > * {
  margin: 0 5px;
}

.container > span > p {
  font-size: 10px;
}

.icon{
  width: 50px;
}
</style>
