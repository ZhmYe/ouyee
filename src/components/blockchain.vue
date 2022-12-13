<template>
    <div id="blockchain" style="width: 100%">
        <div class="blockchain-header">区块链信息</div>
        <div class="blockchain-info">
            <div class="info">
                <div class="info-title">区块链ID:</div>
                <div class="info-content">1</div>
            </div>
            <div class="info">
                <div class="info-title">区块链名称:</div>
                <div class="info-content">ouyeel_chain</div>
            </div>
            <div class="info">
                <div class="info-title">当前连接节点数:</div>
                <div class="info-content">3</div>
            </div>
            <div class="info">
                <div class="info-title">块高度:</div>
                <div class="info-content">32439734</div>
            </div>
            <div class="info">
                <div class="info-title">总交易数:</div>
                <div class="info-content">1458</div>
            </div>
        </div>
        <div class="blockchain-header">新区块</div>
        <div class="block">
            <div style="display: flex;width: 100%">
                <div class="block-info" style="width: 30%">
                    <div class="block-info-title">区块高度:</div>
                    <div class="block-info-content rounded">136</div>
                </div>
                <div class="block-info" style="width: 40%">
                    <div class="block-info-title">时间戳:</div>
                    <div class="block-info-content rounded">2022-12-13 18:32:55</div>
                </div>
            </div>
            <div class="block-info">
                <div class="block-info-title">区块哈希:</div>
                <div class="block-info-content rounded">0xas4d6asd4as6d4a6s4das654d6as4d56a4sd564</div>
            </div>
            <div class="block-info">
                <div class="block-info-title">交易根哈希:</div>
                <div class="block-info-content rounded">0xas4d6asd4as6d4a6s4das654d6as4d56a4sd564</div>
            </div>
            <div class="block-info">
                <div class="block-info-title">状态根哈希:</div>
                <div class="block-info-content rounded">0xas4d6asd4as6d4a6s4das654d6as4d56a4sd564</div>
            </div>
            <button class="btn btn-outline-primary">查看所有区块</button>
        </div>
        <div class="blockchain-header">新交易</div>
        <div class="transaction">
            <div class="transaction-item">
                <div class="transaction-info">
                    <div class="transaction-sign">交易</div>
                    <div class="transaction-detail" style="margin-left: 2%;height: 50px;position: relative;">
                        <div class="transaction-info-content rounded">0x09B1...7D2E</div>
                        <div class="transaction-time" style="color: #33CCCC;font-size: small;">10:37:26</div>
                    </div>
                </div>
                <div class="person-info">
                    <div class="person-info-title">发送方:</div>
                    <div class="person-info-content rounded">0x2b92d0...bae21d</div>
                </div>
                <div class="person-info">
                    <div class="person-info-title">接收方:</div>
                    <div class="person-info-content rounded">0xb5399a...451ea5</div>
                </div>
            </div>
            <div class="transaction-item">
                <div class="transaction-info">
                    <div class="transaction-sign">交易</div>
                    <div class="transaction-detail" style="margin-left: 2%;height: 50px;position: relative;">
                        <div class="transaction-info-content rounded">0x09B1...7D2E</div>
                        <div class="transaction-time" style="color: #33CCCC;font-size: small;">10:37:26</div>
                    </div>
                </div>
                <div class="person-info">
                    <div class="person-info-title">发送方:</div>
                    <div class="person-info-content rounded">0x2b92d0...bae21d</div>
                </div>
                <div class="person-info">
                    <div class="person-info-title">接收方:</div>
                    <div class="person-info-content rounded">0xb5399a...451ea5</div>
                </div>
            </div>
            <div class="transaction-item">
                <div class="transaction-info">
                    <div class="transaction-sign">交易</div>
                    <div class="transaction-detail" style="margin-left: 2%;height: 50px;position: relative;">
                        <div class="transaction-info-content rounded">0x09B1...7D2E</div>
                        <div class="transaction-time" style="color: #33CCCC;font-size: small;">10:37:26</div>
                    </div>
                </div>
                <div class="person-info">
                    <div class="person-info-title">发送方:</div>
                    <div class="person-info-content rounded">0x2b92d0...bae21d</div>
                </div>
                <div class="person-info">
                    <div class="person-info-title">接收方:</div>
                    <div class="person-info-content rounded">0xb5399a...451ea5</div>
                </div>
            </div>
            <div class="transaction-item">
                <div class="transaction-info">
                    <div class="transaction-sign">交易</div>
                    <div class="transaction-detail" style="margin-left: 2%;height: 50px;position: relative;">
                        <div class="transaction-info-content rounded">0x09B1...7D2E</div>
                        <div class="transaction-time" style="color: #33CCCC;font-size: small;">10:37:26</div>
                    </div>
                </div>
                <div class="person-info">
                    <div class="person-info-title">发送方:</div>
                    <div class="person-info-content rounded">0x2b92d0...bae21d</div>
                </div>
                <div class="person-info">
                    <div class="person-info-title">接收方:</div>
                    <div class="person-info-content rounded">0xb5399a...451ea5</div>
                </div>
            </div>
            <div class="transaction-item">
                <div class="transaction-info">
                    <div class="transaction-sign">交易</div>
                    <div class="transaction-detail" style="margin-left: 2%;height: 50px;position: relative;">
                        <div class="transaction-info-content rounded">0x09B1...7D2E</div>
                        <div class="transaction-time" style="color: #33CCCC;font-size: small;">10:37:26</div>
                    </div>
                </div>
                <div class="person-info">
                    <div class="person-info-title">发送方:</div>
                    <div class="person-info-content rounded">0x2b92d0...bae21d</div>
                </div>
                <div class="person-info">
                    <div class="person-info-title">接收方:</div>
                    <div class="person-info-content rounded">0xb5399a...451ea5</div>
                </div>
            </div>
            <button class="btn btn-outline-primary">查看所有交易</button>
        </div>
    </div>
  </template>
  
  <script>

  export default {
    name: 'BlockChain',
    data () {
      return {
      }
    },
    created () {
    },
    mounted () {
    },
    methods: {
    }
  }
  </script>
  <style>
  .blockchain-header {
    height: 50px;
    line-height: 50px;
    margin-left: 1%;
    color: #0099FF;
  }
  #blockchain {
    border: 1px solid #0099FF;
    border-radius: 1rem;
    background: repeating-linear-gradient(#000055, #000022);
    /* font-size: larger; */
    font-weight: 600;
    height: 800px
  }
  .info {
    display: flex;
    width: 90%;
    margin: 0 auto;
    margin-bottom: 5px;
  }
  .info-title {
    width: 50%;
    color: #33CCCC
  }
  .info-content {
    width: 50%;
    color: #33CCCC;
  }
  .block {
    /* margin-left: 5%; */
    margin-top: 10px;
    width: 100%;
    text-align: center;
  }
  .transaction {
    /* margin-left: 5%; */
    margin-top: 10px;
    width: 100%;
    text-align: center;
  }
  .block-info {
    margin-left: 5%;
    display: flex;
    color: #33CCCC;
    margin-bottom: 5px
  }
  .block-info-title {
    height: 30px;
    line-height: 30px;
    text-align: center;
  }
  .block-info-content {
    /* border: 1px solid #33CCCC; */
    /* background-color: #33CCCC; */
    min-width: 100px;
    /* border-radius: 10%; */
    height: 30px;
    line-height: 30px;
    text-align: center;
    color: #33CCCC;
    margin-left: 1%;
  }
  .transaction-item {
    display: flex;
    width: 90%;
    margin: 0 auto;
    margin-top: 2px
  }
  .transaction-info {
    display: flex;
    width: 30%;
  }
  .transaction-sign {
    border-radius: 50%;
    background-color: #33CCCC;
    width: 40px;
    height: 40px;
    line-height: 40px;
    text-align: center;
  }
  .transaction-time {
    height: 20px;
    line-height: 20px;
  }
  .transaction-info-content {
    border: 1px solid #33CCCC;
    /* background-color: #33CCCC; */
    min-width: 100px;
    /* border-radius: 10%; */
    height: 20px;
    line-height: 20px;
    text-align: center;
    color: #33CCCC;
    margin-left: 1%;
    font-size: small;
  }
  .person-info {
    width: 40%;
    display: flex;
    height: 40px;
    line-height: 40px;
    color: #33CCCC;
    /* align-content: center; */
  }
  .person-info-content {
    border: 1px solid #33CCCC;
    /* background-color: #33CCCC; */
    min-width: 100px;
    /* border-radius: 10%; */
    height: 30px;
    line-height: 30px;
    text-align: center;
    color: #33CCCC;
    margin-left: 1%;
    align-self: center;
    /* font-size: large; */
  }
  </style>