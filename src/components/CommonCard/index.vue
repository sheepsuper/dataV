<template>
  <div class="common-card">
    <div class="title">{{title}}</div>
    <div class="value">{{value}}</div>
    <div class="chart"></div>
    <div class="line" />
    <div class="total">5</div>
  </div>
</template>

<script>
export default {
  name: "CommonCard",
  props:{
    title:{
      type: String
    },
    value: {
      type: String
    }
  }
};
</script>

<style lang="scss" scoped>
.title {
  font-size: 12px;
  color: #999;
}
.value {
  font-size: 25px;
  color: #333;
  margin-top: 5px;
  letter-spacing: 1px;
}
.chart {
  height: 50px;
  background: brown;
}
.line {
  margin: 10px 0;
  border-top: 1px solid #eeeeee;
}
.total {
  font-size: 12px;
  color: #666666;
}
</style>
