<template>
  <div class="left-nav">
    <ul>
      <li>
        <i class="icon iconfont icon-hongbao"></i>
        <div>支付</div>
      </li>
      <li>
        <i class="icon iconfont icon-kucun"></i>
        <div>店铺</div>
      </li>
      <li>
        <i class="icon iconfont icon-shangpin"></i>
        <div>商品</div>
      </li>
      <li>
        <i class="icon iconfont icon-diamond"></i>
        <div>会员</div>
      </li>
      <li>
        <i class="icon iconfont icon-zhangdan"></i>
        <div>数据</div>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'leftNav',
  data () {
    return {}
  }
}
</script>

<style lang="scss">
.left-nav {
  float: left;
  widows: 5%;
  height: 100%;
  font: 16px/1.5;
  background-color: rgb(102, 158, 231);
  color: #fff;
  ul {
    padding: 0px;
    margin: 0px;
    li {
      list-style: none;
      text-align: center;
      border-bottom: 1px solid #fff;
      padding: 10px;
      .iconfont {
        font-size: 25px;
      }
    }
  }
}
</style>
