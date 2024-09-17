<script>
export default {
  data() {
    return {
    };
  }

}
</script>

<template>
  <footer>
    <div class="link-footer">
      <div class="container row">
        <div class="col-1-3">
          <div>
            <h4>DC COMICS</h4>
            <ul>
              <li>
                <a href="#">Characters</a>
              </li>
              <li>
                <a href="#">Comics</a>
              </li>
              <li>
                <a href="#">Movies</a>
              </li>
              <li>
                <a href="#">TV</a>
              </li>
              <li>
                <a href="#">Games</a>
              </li>
              <li>
                <a href="#">Videos</a>
              </li>
              <li>
                <a href="#">News</a>
              </li>
            </ul>
          </div>
          <div>
            <h4>SHOP</h4>
            <ul>
              <li>
                <a href="#">Shop DC</a>
              </li>
              <li>
                <a href="#">Shop DC Collectibles</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div class="sign-footer">

    </div>
  </footer>
</template>

<style scoped>
footer{
  height: 400px;
  background-image: url(../assets/vue-dc-comics-1/img/footer-bg.jpg);
}

.link-footer{
  color:white;
  display: inline-block;
  margin-bottom: 40px;
}

.link-footer div{
  padding-top: 35px;
  margin: 0px 0 10px 0;
}

.link-footer div ul{
  list-style: none;
}

.link-footer div h4{
  margin-bottom: 10px;
}

.link-footer div ul li{
  margin-bottom: 2px;
}

.link-footer div ul li a{
  text-decoration: none;
  color: grey;
  margin: 5px 0;
}

.sign-footer{
  height: 100px;
  background-color: #303030;
}

</style>
