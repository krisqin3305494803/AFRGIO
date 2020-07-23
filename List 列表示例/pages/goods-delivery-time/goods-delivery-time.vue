<template>
		<view >
			<uni-nav-bar left-icon="back"  title="常见问题"></uni-nav-bar>
		<view class="container">
			 <view class="uni-flex uni-column">
                <view class="flex-top">
						<view class="contant">
							订单拼团成功后，常规类项目商品成团后48小时内发货，品质水果类目商品成团后24小时内发货，直邮类目商品成团后120小时发货，直供类目商品成团后168小时内发货，预售类目商品在预售时间内发货，抽奖和免费是哟ing商品在开奖候48小时内发货，具体活动以活动发货时间为准~
						</view>
						<view>
							<legend class="problem">
							以上方案是否解决了您的问题？
							</legend>
						</view>
						<view class="btn">
							<button type="default">已解决</button><button type="default">未解决</button>
						</view>
				</view>
                <view class="flex-end">联系客服</view>
            </view>
			</view>
           
		</view>
</template>

<script>
	import uniTag from "@/components/uni-tag/uni-tag.vue"
	import uniNavBar from "@/components/uni-nav-bar/uni-nav-bar.vue"
	import uniSection from '@/components/uni-section/uni-section.vue'
	import uniList from '@/components/uni-list/uni-list.vue'
	import uniListItem from '@/components/uni-list-item/uni-list-item.vue'
	export default {
		components: {
			components: {uniNavBar},
			components: {uniTag},
			uniSection,
			uniList,
			uniListItem
		},
		data() {
			return {
			}
		},
		methods: {
		
			}
		}
</script>

<style>
	/* 头条小程序组件内不能引入字体 */
	/* #ifdef MP-TOUTIAO */
	@font-face {
		font-family: uniicons;
		font-weight: normal;
		font-style: normal;
		src: url('~@/static/uni.ttf') format('truetype');
	}
	
	/* #endif */
	
	/* #ifndef APP-NVUE */
	page {
		display: flex;
		flex-direction: column;
		box-sizing: border-box;
		background-color: #efeff4;
		min-height: 100%;
		height: auto;
	}
	
	view {
		font-size: 14px;
		line-height: inherit;
	}
	
	/* #endif */
	.example {
		padding: 0 15px;
	}
	
	.container{
		width: 100%;
		position: relative;
	}
	.contant{
		padding-top: 1rem;
		width: 100%;
		text-align: left;
	}
	.problem{
		margin-top: 3rem;
		text-align: center;
	}
	.btn{
		margin-top: 1rem;
	}
	.flex-top{
		background-color: #FFFFFF;
		font-size: 14;
	}
	.flex-end{
	height: 2rem;
    position: fixed;
    bottom: 0;
    left: 0;
    width: 100%;
    line-height: normal;
    background-color: #fff;
    z-index: 10;
    display: -webkit-box;
    display: -webkit-flex;
    display: flex;
    -webkit-box-align: center;
    -webkit-align-items: center;
    align-items: center;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    justify-content: center;
    box-shadow: 0 -0.01rem 0.03rem rgba(0,0,0,.1);
}
	
</style>
