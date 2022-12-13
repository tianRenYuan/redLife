<template>
	<view class="uni-wrap">
			<view class="example-info">
			<img decoding="async" loading="lazy" src="https://img.51miz.com/Element/00/22/53/10/07e8259c_E225310_7ca70203.png" alt="图片文本描述" width="300" height="200">
			</view>
	</view>
	     <view class="vipCard">
	                        <view class="flex justify-around align-center">
	                            <view class="margin-right-lg text-lg" style="color: snow">VIP会员 | <text class="margin-left-xs text-sm">2022-11-15到期</text></view>
	                            <button class="cu-btn btnSize " >立即续费</button>
	                        </view>
	                    </view>
</template>


<script>
	export default {
		data() {
			return {
			}
		},
		onReady() {

		},
		methods: {

		}
	}
</script>
<style lang="scss">
  $uni-success: #18bc37 !default;

	.uni-wrap {
		flex-direction: column;
		/* #ifdef H5 */
		height: calc(100vh - 44px);
		/* #endif */
		/* #ifndef H5 */
		height: 100vh;
		/* #endif */
		flex: 1;
	}

	.mb-10 {
		margin-bottom: 10px;
	}

  .decoration{
    width: 6px;
    height: 6px;
		margin-right: 4px;
    border-radius: 50%;
		background-color: $uni-success;
  }
      .vipCard {
          position: absolute;
          background-image: linear-gradient(to right,#F37B1D,#E55349);
          width: 90%;
          bottom: 0;
          margin-left: 5%;
          padding: 30rpx;
          border-radius: 25px 25px 0px 0px ;
      .hp {
          position: absolute;
          border-radius:  55px 55px 0px 0px;
      }
          .btnSize {
              height: 60rpx;
              color: #E65B49;
              font-size: 0.8rem;
              border-radius: 45px 45px 45px 45px ;
          }
      }
</style>
