<template>
  <div id="app">
    <div class="mynav fixed-top">
    <ul>
      <img src="/static/images/ECNU.ico" class="rounded-circle logo-photo" alt="" style="height:100%">
      <h4 style="font-weight: 600">&nbsp;&nbsp;华东师大-欧冶区块链平台</h4>
      <!-- <li><a class="active"><i class="fa fa fa-bar-chart"></i>Evaluation</a></li> -->
      <!-- <li><a class="active"><i class="fa fa fa-bookmark"></i>Overview</a></li> -->
      <div class="time">
        <div class="timer" style="height: 50px; line-height: 50px;margin-right: 10px;font-size: larger;font-weight: 600;"><p>16:55:10</p></div>
        <div class="date">
          <div class="day" style="font-weight: 600">2022/12/13</div>
          <div class="week" style="font-weight: 600">星期二</div>
        </div>
      </div>
    </ul>
    </div>
    <!-- <BlockReplicating></BlockReplicating> -->
    <div class="sidebar position-fixed" id="sidebar">
      <br>
      <img src='/static/images/default.png' class="rounded-circle head-photo" alt="">
      <br><br>
      <h4><strong><span>菜单</span></strong></h4>
      <div class="line-split mx-auto"></div>
      <ul>
        <li>
          <a><i class="fa fa-address-card-o"></i><span>个人信息</span></a>
        </li>
        <li>
          <a><i class="fa fa-pencil"></i><span>修改密码</span></a>
        </li>
        <li>
          <a><i class="fa fa-user-times"></i><span>注销用户</span></a>
        </li>
        <li>
          <a href="/"><i class="fa fa-calendar-times-o"></i><span>退出登录</span></a>
        </li>
      </ul>
      <br>
      <h4><strong><span>服务</span></strong></h4>
      <div class="line-split mx-auto"></div>
      <ul>
        <li>
          <a><i class="fa fa fa-bookmark-o"></i><span>回到主页</span></a>
        </li>
        <li>
           <a><i class="fa fa-address-book-o"></i><span>发起请求</span></a>
        </li>
        <li>
          <a><i class="fa fa-book"></i><span>我的发票</span></a>
        </li>
      </ul>
      <br><br>
    </div>
    <div style="position: relative;top: 100px; left: 90px;display: flex;width: calc(100% - 90px);">
      <div style="width: 60%;">
        <InvoiceComponent></InvoiceComponent>
        <FigureComponent></FigureComponent>
      </div>
      <BlockChain style="width: 39%; margin-left: 1%"></BlockChain>
    </div>
  </div>
</template>

<script>
import InvoiceComponent from './components/invoice.vue';
import BlockChain from './components/blockchain.vue'
import FigureComponent from './components/figure.vue'
export default {
  name: 'App',
  components: {
    InvoiceComponent,
    BlockChain,
    FigureComponent
  }
}
</script>

<style>
</style>
