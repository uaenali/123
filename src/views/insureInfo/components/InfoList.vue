<template>
  <div class="list">
    <div class="info-item">
      <div class="title">投保人信息</div>
      <div class="userinfo">
        <div class="identity">
          <span class="name">李四四</span>
          <span class="line">|</span>
          男
          <span class="line">|</span>
          1990-01-01
        </div>
        <div class="id-card">
          居民身份证
          <span class="line">|</span>
          110101199001011010
        </div>
      </div>
    </div>
    <!-- 投保人信息 -->
    <div class="info-item">
      <div class="title">投保人信息</div>
      <div class="userinfo">
        <div class="identity">
          <span class="name">李四四</span>
          <span class="line">|</span>
          男
          <span class="line">|</span>
          1990-01-01
        </div>
        <div class="id-card">
          居民身份证
          <span class="line">|</span>
          110101199001011010
        </div>
      </div>
    </div>
    <div class="beneficiary">
      <div class="title">受益人信息</div>
      <div class="type">法定受益人</div>
    </div>
    <!-- 险种信息 -->
    <div class="kind">
        <div class="title">险种信息</div>
        <div class="critical">
            <div class="intro">
              <h2>重疾险（卓越版）重大疾病保险</h2>
              <div class="cost">
                  <span class="premium">保费：734.6元</span>
                  <span class="base">基本保额：20000元</span>
              </div>
          </div>
          <div class="time">
            <span class="payment">缴费期限：20年</span>
            <span class="period ">保险期限：终身</span>
          </div>  
        </div>
              
                
         <!-- 险种信息 生效日 -->
        
          <div class="bg">
            <div class="effective">指定生效日：否</div>
            <div class="autopay">现金价值自动垫交：是</div>
          </div>
    </div>
   <!-- 转账信息 -->
        <div class="transfer">
          <div class="title">转账信息</div>
            <div class="transinfo">
              <span class="name">李四四</span>
              <span class="line">|</span>
              农业银行
              <span class="line">|</span>
              北京市&nbsp;北京市
            </div>
            <div class="bank">
                <span class="card">62222&nbsp;2222&nbsp;2222&nbsp;2222&nbsp;222</span>
                <span class="amount">转账金额：734.6元</span>
            </div>
        </div>

        <!-- 签名 -->
        <div class="sign">
          <div class="title">签名</div>
          <div class="sign-part">
            <span class="word13">请投保人、被保险人</span>
            <span class="word14">李四四</span>
            <span class="word15">亲笔签名</span>
            <img src="" alt="">
          </div>

            
        </div>








  </div>
</template>

<style lang="scss" scoped>
// @import '../base.scss';
.list {
  padding: 0 10px;
}
.info-item {
  color: #999;
  //   background: #F4F4F4;
  padding: 18px 0;
  .title {
    height: 38px;
    background: linear-gradient(90deg, #ff9f06 0%, #ffba55 100%);
    border-radius: 5px 5px 0px 0px;
    color: #fff;
    font-weight: 500;
    font-size: 16px;
    line-height: 38px;
    padding: 0 10px;
  }
  .userinfo {
    padding: 10px 18px;
    background-color: #fff;
    font-weight: 400;
    .name {
      color: #000000;
    }
    .line {
      margin: 0 5px;
    }

    .id-card {
      padding-top: 18px;
      padding-bottom: 10px;
    }
  }
}

.beneficiary {
  padding: 10px 0;
  .title {
    height: 38px;
    background: linear-gradient(90deg, #ff9f06 0%, #ffba55 100%);
    border-radius: 5px 5px 0px 0px;
    color: #fff;
    font-weight: 500;
    font-size: 16px;
    line-height: 38px;
    padding: 0 10px;
  }
  .type {
    background-color: #fff;
    height: 48px;
    line-height: 48px;
    padding-left: 10px;
    font-size: 14px;
    font-family: PingFangSC-Regular, PingFang SC;
    font-weight: 400;
    color: #333333;
  }
}

.kind {
    .title {
    height: 38px;
    background: linear-gradient(90deg, #ff9f06 0%, #ffba55 100%);
    border-radius: 5px 5px 0px 0px;
    color: #fff;
    font-weight: 500;
    font-size: 16px;
    line-height: 38px;
    padding: 0 10px;
  }
  .critical {
    .intro {
      color: red;
  }
  h2 {
    font-size: 16px;
    font-family: PingFangSC-Regular, PingFang SC;
    font-weight: 400;
    color: #333333;
    padding: 12px 10px;

  }
  .cost {
      color: #999;
      margin-top: 10px;
      .premium {
        font-size: 16px;
        font-family: PingFangSC-Medium, PingFang SC;
        font-weight: 500;
        line-height: 22px;
    }
        .base {
            padding-left:67px;
        }

  }
    .time {
        color: #999;
        margin-top: 20px;
        .period {
            padding-left:59px;
        }
    }
}
  }
  


    .bg {
        background-color: #fff;
        padding-left: 10px;
        color: #999;
        .effective {
            margin-top: 10px;
        }
        .autopay {
            margin-top: 10px;
            margin-bottom: 10px;
            
        }
    }
    .transfer {
        background-color: #fff;
        .title {
            height: 38px;
            background: linear-gradient(90deg, #ff9f06 0%, #ffba55 100%);
            border-radius: 5px 5px 0px 0px;
            color: #fff;
            font-weight: 500;
            font-size: 16px;
            line-height: 38px;
            padding: 0 10px;
       }
       .transinfo {
           padding-left: 10px;
           margin-top: 10px;
           font-size:14px;
           font-weight: 400;
           color: #999;
           .name {
                color: #333333;
           }
           
       }
       .bank {
           padding-left: 10px;
           color: #999;
           margin-top: 10px;
           .amount {
               margin-left: 18px;
               margin-right: 11px;
           }
       }
    }

</style>
