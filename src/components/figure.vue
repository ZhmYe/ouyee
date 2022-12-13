<template>
    <div id="figure" style="width: 100%;">
        <div class="info-nav">
            <div :class="getinfoChooseStyle(0)" v-on:click="changeinfoChoose($event, 0)">实时交易数据</div>
            <div :class="getinfoChooseStyle(1)" v-on:click="changeinfoChoose($event, 1)">发票类型统计</div>
        </div>
    </div>
  </template>
  
  <script>

  export default {
    name: 'FigureComponent',
    data () {
      return {
        infoChoose: 0
      }
    },
    created () {
    },
    mounted () {
    },
    methods: {
        changeinfoChoose: function(event, index) {
            this.infoChoose = (this.infoChoose == index) ? this.infoChoose : index
        },
        getinfoChooseStyle: function(index) {
            return (this.infoChoose == index) ? "info-nav-item info-active" : "info-nav-item info-not-active"
        }
    }
  }
  </script>
  <style>
    #figure {
    border: 1px solid #0099FF;
    border-radius: 1rem;
    background: repeating-linear-gradient(#000055, #000022);
    /* font-size: larger; */
    font-weight: 600;
    height: 390px;
    margin-top: 10px;
  }
    .info-nav {
    margin-left: 1%;
    display: flex;
    width: 100%;
    margin-top: 10px;
    /* margin-top: 20px */
  }
  .info-nav-item {
    width: 10%;
    text-align: center;
    height: 30px;
    line-height: 30px;
  }
  .info-active {
    border-top: 1px solid #00FFFF;
    border-left: 1px solid #00FFFF;
    border-right: 1px solid #00FFFF;
    background-color: #00FFFF;
  }
  .info-not-active {
    border-bottom: 1px solid #00FFFF;
    color: #00FFFF;
  }
  </style>