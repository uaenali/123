<template>
  <div class="page">
    <Header />
    <div class="service">
      <span class="waiter">服务专员：</span>
      <span class="info">张三三</span>
      <img class="orangedot" src="./assets/img/orangedot.png" alt="" />
      <img class="tel" src="./assets/img/tel.png" alt="" />
    </div>
    <InfoList></InfoList>
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import InfoList from "./components/InfoList.vue";
export default {
  components: {
    Header,
    InfoList,
  },
};
</script>

<style lang="scss" scoped>
.page {
  background-color: #f4f4f4;
}
.service {
  background-color: #fff;
  height: 28px;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  font-size: 12px;
  font-family: PingFangSC-Regular, PingFang SC;
  font-weight: 400;
  color: #333333;

  .info {
    margin-left: 5px;
    margin-right: 6px;
  }
  .tel {
    margin-left: -11px;
  }
}
</style>
