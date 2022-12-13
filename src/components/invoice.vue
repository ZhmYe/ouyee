<template>
    <div id="invoice" style="width: 100%;">
        <div class="invoice-header">发票数据上链</div>
        <div class="invoice-table">
            <table class="table table-hover">
                <thead>
                <tr>
                    <th style="color: #3366FF">区块链高度</th>
                    <th style="color: #3366FF">购买方</th>
                    <th style="color: #3366FF">销售方</th>
                    <th style="color: #3366FF">发票类型</th>
                    <th style="color: #3366FF">税点</th>
                    <th style="color: #3366FF">价费</th>
                    <th style="color: #3366FF">税费</th>
                    <th style="color: #3366FF">价税合计</th>
                </tr>
                </thead>
                <tbody>
                <tr>
                    <td style="color: #33CCCC">914</td>
                    <td style="color: #33CCCC">海通证券</td>
                    <td style="color: #33CCCC">维宏股份</td>
                    <td style="color: #33CCCC">增值税发票</td>
                    <td style="color: #33CCCC">13%</td>
                    <td style="color: #33CCCC">83324</td>
                    <td style="color: #33CCCC">214</td>
                    <td style="color: #33CCCC">83438</td>
                </tr>
                <tr>
                    <td style="color: #33CCCC">914</td>
                    <td style="color: #33CCCC">海通证券</td>
                    <td style="color: #33CCCC">维宏股份</td>
                    <td style="color: #33CCCC">增值税发票</td>
                    <td style="color: #33CCCC">13%</td>
                    <td style="color: #33CCCC">83324</td>
                    <td style="color: #33CCCC">214</td>
                    <td style="color: #33CCCC">83438</td>
                </tr>
                <tr>
                    <td style="color: #33CCCC">914</td>
                    <td style="color: #33CCCC">海通证券</td>
                    <td style="color: #33CCCC">维宏股份</td>
                    <td style="color: #33CCCC">增值税发票</td>
                    <td style="color: #33CCCC">13%</td>
                    <td style="color: #33CCCC">83324</td>
                    <td style="color: #33CCCC">214</td>
                    <td style="color: #33CCCC">83438</td>
                </tr>
                <tr>
                    <td style="color: #33CCCC">914</td>
                    <td style="color: #33CCCC">海通证券</td>
                    <td style="color: #33CCCC">维宏股份</td>
                    <td style="color: #33CCCC">增值税发票</td>
                    <td style="color: #33CCCC">13%</td>
                    <td style="color: #33CCCC">83324</td>
                    <td style="color: #33CCCC">214</td>
                    <td style="color: #33CCCC">83438</td>
                </tr>
                <tr>
                    <td style="color: #33CCCC">914</td>
                    <td style="color: #33CCCC">海通证券</td>
                    <td style="color: #33CCCC">维宏股份</td>
                    <td style="color: #33CCCC">增值税发票</td>
                    <td style="color: #33CCCC">13%</td>
                    <td style="color: #33CCCC">83324</td>
                    <td style="color: #33CCCC">214</td>
                    <td style="color: #33CCCC">83438</td>
                </tr>
                <tr>
                    <td style="color: #33CCCC">914</td>
                    <td style="color: #33CCCC">海通证券</td>
                    <td style="color: #33CCCC">维宏股份</td>
                    <td style="color: #33CCCC">增值税发票</td>
                    <td style="color: #33CCCC">13%</td>
                    <td style="color: #33CCCC">83324</td>
                    <td style="color: #33CCCC">214</td>
                    <td style="color: #33CCCC">83438</td>
                </tr>
                </tbody>
            </table>
        </div>
    </div>
  </template>
  
  <script>

  export default {
    name: 'InvoiceComponent',
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
  .invoice-header {
    height: 50px;
    line-height: 50px;
    margin-left: 1%;
    color: #0099FF;
  }
  #invoice {
    border: 1px solid #0099FF;
    border-radius: 1rem;
    background: repeating-linear-gradient(#000055, #000022);
    /* font-size: larger; */
    font-weight: 600;
    height: 400px;
  }
  .invoice-table {
    width: 85%;
    margin: 0 auto;
  }
  </style>