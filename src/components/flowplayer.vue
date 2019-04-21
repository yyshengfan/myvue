<template>
  <div class="flowplayer">

  <div class="banner">

    <div class="xt-focusBox">

      <ul class="pic">

        <li>
          <a href="javascript:void(0)"><img src="../../static/link/images/14921571030140.jpg"></a>
        </li>

        <li>
          <a href="javascript:void(0)"><img src="../../static/link/images/14921571110274.jpg"></a>
        </li>

        <li>
          <a href="javascript:void(0)"><img src="../../static/link/images/14921571190460.jpg"></a>
        </li>

      </ul>

      <ul class="mu">

        <li></li>

        <li></li>

        <li></li>

      </ul>

    </div>

  </div>

  <!-- <video autoplay="">

<source src="../../static/link//themes/default/themes/images/Final-0914-3.mp4" type="video/mp4">

</video> -->

</div>
</template>
<script type="text/javascript" src="../../static/link/js/jquery1.42.min.js"></script>
<script type="text/javascript" src="../../static/link/js/jquery.SuperSlide.2.1.js"></script>
<script type="text/javascript">
  jQuery(".xt-focusBox").slide({
    mainCell: ".pic",
    effect: "fold",
    autoPlay: true,
    delayTime: 600,
    trigger: "click"
  });
</script>
<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.xt-focusBox {
  position: relative;
  width: 100%;
  height: 400px;
  overflow: hidden;
  padding-top: 0px
}

.xt-focusBox .pic {
  position: relative;
  z-index: 0;
  overflow: hidden;
}

.xt-focusBox .pic li {
  width: 100%;
  left: 50%;
}

.xt-focusBox .pic .bgcolor1 {
  z-index: 1;
}

.xt-focusBox .pic img {
  width: 100%;
  height: 400px;
  display: block;
  margin: 0 auto;
}

.xt-focusBox .mu {
  width: 100%;
  position: absolute;
  bottom: 10px;
  text-align: center;
  font-size: 0;
  z-index: 1;
}

.xt-focusBox .mu li {
  margin: 0 5px;
  background: url(../../static/link/images/dot.png) no-repeat 0 -10px;
  height: 13px;
  overflow: hidden;
  width: 36px;
  cursor: pointer;
  display: inline-block;
  *display: inline;
  zoom: 1;
  _background: url(../../static/link/images/dot8.png) no-repeat 0 -16px;
}

.xt-focusBox .mu .on {
  background-position: 0 0;
}
</style>
