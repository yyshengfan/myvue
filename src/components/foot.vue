<template>
  <div id="footer">

    <div class="container">

      <div class="row">

        <div class="span3" style=" width:240px">

          <div class="bottom-logo"><img src="../../static/link/images/logo.png" alt="" /></div>

          <p style="color:#fff;font-weight:normal; font-size:12px;">联系邮箱</br>
            info@yyshengfaninfo.com						</p>

        </div>

        <div class="span3" style="width:150px">
          <a class="dropdown-toggle" role="button" href="javascript:void(0)">

            <h5>选择YYSHENGFAN</h5>

          </a>

          <ul class="animated">

            <li>
              <a href='../../static/link/about.html' tabindex="-1">关于YYSHENGFAN</a>
            </li>

            <li>
              <a href='../../static/link/protocol.html' tabindex="-1">公司条款协议</a>
            </li>

            <li>
              <a href='../../static/link/risk.html' tabindex="-1">投资风险提示</a>
            </li>

            <li>
              <a href='../../static/link/Q&A.html' tabindex="-1">常见问题解答</a>
            </li>

          </ul>

        </div>

        <div class="span3" style="width:150px">
          <a class="dropdown-toggle" role="button" href="javascript:void(0)">

            <h5>交易产品</h5>

          </a>

          <ul class="animated">

            <li>
              <a href='../../static/link/exchange.html' tabindex="-1">外汇交易产品</a>
            </li>

            <li>
              <a href='../../static/link/precious.html' tabindex="-1">贵金属交易类</a>
            </li>

            <li>
              <a href='../../static/link/oil.html' tabindex="-1">国际原油交易</a>
            </li>

            <li>
              <a href='../../static/link/transaction.html' tabindex="-1">产品交易信息</a>
            </li>

          </ul>

        </div>

        <div class="span3" style="width:150px">
          <a class="dropdown-toggle" role="button" href="javascript:void(0)">

            <h5>交易平台</h5>

          </a>

          <ul class="animated">

            <li>
              <a href='../../static/link/soft-pc.html' tabindex="-1">PC桌面版软件</a>
            </li>

            <li>
              <a href='../../static/link/soft-phone.html' tabindex="-1">手机交易软件</a>
            </li>

            <li>
              <a href='../../static/link/#' target="_blank" tabindex="-1">开设真实账户</a>
            </li>

            <li>
              <a href='../../static/link/#' target="_blank" tabindex="-1">注册模拟账户</a>
            </li>

            <!--<li>
              <a href='../../static/link/#' tabindex="-1">注册代理账户</a>
            </li>-->

          </ul>

        </div>

        <div class="span3" style="width:150px">
          <a class="dropdown-toggle" role="button" href="javascript:void(0)">

            <h5>交易学院</h5>

          </a>

          <ul class="animated">

            <!--<li>
              <a href='../../static/link/calendar.html' tabindex="-1">财经日历信息</a>
            </li>-->

            <li>
              <a href='../../static/link/anewslist1.html?id=1' tabindex="-1">外汇市场分析</a>
            </li>

            <li>
              <a href='../../static/link/anewslist1.html?id=2' tabindex="-1">财经新闻资讯</a>
            </li>

            <li>
              <a href='../../static/link/anewslist1.html?id=3' tabindex="-1">外汇行情资讯</a>
            </li>

          </ul>

        </div>

        <div class="span3" style="width:150px">
          <a class="dropdown-toggle" role="button" href="javascript:void(0)">

            <h5>代理合作</h5>

          </a>

          <ul class="animated">

            <li>
              <a href='../../static/link/recommend.html' tabindex="-1">朋友推荐计划</a>
            </li>

            <li>
              <a href='../../static/link/#' tabindex="-1">IB代理申请</a>
            </li>

            <li>
              <a href='../../static/link/cooperation.html' tabindex="-1">白标合作机会</a>
            </li>

            <!--<li>
              <a href='../../static/link/#' tabindex="-1">提交代理申请</a>
            </li>-->

          </ul>

        </div>

      </div>

    </div>

  </div>
</template>

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
.flowplayer {
  width: 100%;
}

.fp-timeline {
  display: none
}

.fp-controls {
  display: none
}

.fp-fullscreen {
  display: none
}

.fp-elapsed {
  display: none
}

.fp-remaining {
  display: none
}

.fp-duration {
  display: none
}

.fp-embed {
  display: none
}

.fp-message {
  display: none
}

.icon_wrapper img {
  transition: all 0.8s ease-in-out;
}

.icon_wrapper img:hover {
  -webkit-transform: rotate(360deg);
  -moz-transform: rotate(360deg);
  -ms-transform: rotate(360deg);
  -o-transform: rotate(360deg);
}

#icon_wrapper img {
  transition: all 0.8s ease-in-out;
}

#icon_wrapper img:hover {
  -webkit-transform: rotatey(360deg);
  -moz-transform: rotatey(360deg);
  -ms-transform: rotatey(360deg);
  -o-transform: rotatey(360deg);
}
</style>
