<template>
  <div class="navbar navbar-fixed-top">

    <div class="navbar-inner">
      
      <div class="container">
        <a class="btn btn-default btn-dropnav" data-target=".nav-collapse"> <span class="icon-bar"></span> <span class="icon-bar"></span> <span class="icon-bar"></span> </a>
        <a class="brand" href="index.html"><img src="../../static/link/images/logo.png" alt="" /></a>

        <div class="nav-collapse collapse">

          <ul class="nav pull-right animated">

            <li class="dropdown">
              <a class="dropdown-toggle" role="button" href="javascript:void(0)">YYSHENGFAN</a>

              <ul class="dropdown-menu" role="menu">

                <li>
                  <a href='about.html' tabindex="-1">关于YYSHENGFAN</a>
                </li>

                <li>
                  <a href='protocol.html' tabindex="-1">公司条款协议</a>
                </li>

                <li>
                  <a href='risk.html' tabindex="-1">投资风险提示</a>
                </li>

                <li>
                  <a href='Q&A.html' tabindex="-1">常见问题解答</a>
                </li>

              </ul>

            </li>

            <li class="dropdown">
              <a class="dropdown-toggle" role="button" href="javascript:void(0)">交易产品</a>

              <ul class="dropdown-menu" role="menu">

                <li>
                  <a href='exchange.html' tabindex="-1">外汇交易产品</a>
                </li>

                <li>
                  <a href='precious.html' tabindex="-1">贵金属交易类</a>
                </li>

                <li>
                  <a href='oil.html' tabindex="-1">国际原油交易</a>
                </li>

                <li>
                  <a href='transaction.html' tabindex="-1">产品交易信息</a>
                </li>

              </ul>

            </li>

            <li class="dropdown">
              <a class="dropdown-toggle" role="button" href="javascript:void(0)">交易平台</a>

              <ul class="dropdown-menu" role="menu">

                <li>
                  <a href='soft-pc.html' tabindex="-1">PC桌面版软件</a>
                </li>

                <li>
                  <a href='soft-phone.html' tabindex="-1">手机交易软件</a>
                </li>

                <li>
                  <a href='#' target="_blank" tabindex="-1">开设真实账户</a>
                </li>

                <li>
                  <a href='#' target="_blank" tabindex="-1">注册模拟账户</a>
                </li>

                <!--<li>
                  <a href='#' tabindex="-1">注册代理账户</a>
                </li>-->

              </ul>

            </li>

            <li class="dropdown">
              <a class="dropdown-toggle" role="button" href="javascript:void(0)">交易学院</a>

              <ul class="dropdown-menu" role="menu">

                <!--<li>
                  <a href='calendar.html' tabindex="-1">财经日历信息</a>
                </li>-->

                <li>
                  <a href='anewslist1.html?id=1' tabindex="-1">外汇市场分析</a>
                </li>

                <li>
                  <a href='anewslist1.html?id=2' tabindex="-1">财经新闻资讯</a>
                </li>

                <li>
                  <a href='anewslist1.html?id=3' tabindex="-1">外汇行情资讯</a>
                </li>

              </ul>

            </li>

            <li class="dropdown">
              <a class="dropdown-toggle" role="button" href="javascript:void(0)">代理合作</a>

              <ul class="dropdown-menu" role="menu">

                <li>
                  <a href='recommend.html' tabindex="-1">朋友推荐计划</a>
                </li>

                <li>
                  <a href='#' tabindex="-1">IB代理申请</a>
                </li>

                <li>
                  <a href='cooperation.html' tabindex="-1">白标合作机会</a>
                </li>

                <!--<li>
                  <a href='#' tabindex="-1">提交代理申请</a>
                </li>-->

              </ul>

            </li>

            <li class="dropdown">
              <a class="dropdown-toggle" role="button" href="javascript:void(0)">公告活动</a>

              <ul class="dropdown-menu" role="menu">

                <li>
                  <a href='anewslist1.html?id=4' tabindex="-1">公告发布</a>
                </li>

                <li>
                  <a href='anewslist1.html?id=5' tabindex="-1">最新活动</a>
                </li>

              </ul>

            </li>

            <!--<li class="dropdown">
              <a class="dropdown-toggle" role="button" href="http://manage.jrsfin.com">客户登录</a>

            </li>

            <img style="float:left; margin-left:-15px; margin-top:20px" src="../../static/link/images/iconhot.png" alt="" />-->

          </ul>

        </div>

        <div class="nav-btn">
          <a href='#' target="_blank" class="btn btn-success ">开设真实账户</a>
          <a href="#" class="btn btn-primary " target="_blank">注册模拟账户</a>

          <div class="btn-group">

            <a class="btn btn-default dropdown-toggle" style='width:60px;' data-toggle="dropdown"> 语言 </a>

            <ul class="dropdown-menu default-dropdown" style='margin-top:0; min-width:60px;' role="menu">

              <li>
                <a href="/">简体中文</a>
              </li>

              <!--li>
                <a href="#">繁體中文</a>
              </li-->

              <li>
                <a href="/en/index.html">English</a>
              </li>

            </ul>

          </div>

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
