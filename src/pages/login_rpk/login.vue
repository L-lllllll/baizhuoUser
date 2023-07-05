<template>
  <view>
    <text class="h2">供应链用户小程序</text>
    <view class="logo"></view>
    <div class="btn">
      <button class="button" type="primary">微信快捷登录</button>
      <button class="button" type="default">手机号登录</button>
    </div>
    <view class="user_agreement">
      <label class="radio">
        <radio value="r2" color="#fe402a" />
        <text>我已阅读并同意</text>
        <navigator href="#">
          《用户服务协议》
        </navigator>
        <text>和</text>
        <navigator href="#">《隐私政策》</navigator>
      </label>
    </view>
  </view>
</template>

<script>
import Vue from 'vue';
export default Vue.extend({
  components: {},
  data() {
    return {}
  },
  computed: {},
  methods: {},
  watch: {},

  // 页面周期函数--监听页面加载
  onLoad() {},
  // 页面周期函数--监听页面初次渲染完成
  onReady() {},
  // 页面周期函数--监听页面显示(not-nvue)
  onShow() {},
  // 页面周期函数--监听页面隐藏
  onHide() {},
  // 页面周期函数--监听页面卸载
  onUnload() {},
  // 页面处理函数--监听用户下拉动作
  // onPullDownRefresh() { uni.stopPullDownRefresh(); },
  // 页面处理函数--监听用户上拉触底
  // onReachBottom() {},
  // 页面处理函数--监听页面滚动(not-nvue)
  // onPageScroll(event) {},
  // 页面处理函数--用户点击右上角分享
  // onShareAppMessage(options) {},
}) 
</script>

<style scoped>
.h2 {
  display: block;
  font-size: 42rpx;
  font-weight: 700;
  text-align: center;
  margin: 80rpx 0;
}
.logo {
  width: 500rpx;
  height: 150rpx;
  background: #fe402a;
  margin: 0 auto 100rpx;
}
button {
  width: 90%;
  border-radius: 50rpx;
  font-size: 36rpx;
  line-height: 2.5;
  margin-bottom: 30rpx;
}
radio {
  transform: scale(0.7);
  margin-top: -4rpx;
}
.user_agreement  {
  width: 100%;
  position: absolute;
  bottom: 100rpx;
  left: 50%;
  transform: translate(-50%);
}
.user_agreement label {
  display: flex;
  justify-content: center;
}
navigator {
  color: #fe402a;
}
button[type=default]:active {
  background: none !important;
}
button[type=primary]:active {
  background-color: #fe402a;
}
</style>