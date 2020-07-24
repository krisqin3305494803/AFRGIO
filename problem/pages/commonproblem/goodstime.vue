<template>
	<view>
		<view class="box">
				<text class="contain">订单拼团成功后，常规类项目商品成团后48小时内发货，品质水果类目商品成团后24小时内发货，直邮类目商品成团后120小时发货，直供类目商品成团后168小时内发货，预售类目商品在预售时间内发货，抽奖和免费是哟ing商品在开奖候48小时内发货，具体活动以活动发货时间为准~ </text>
			<view class="mid">
				<view class="promlem">
					<text>以上方案是否解决了您的问题？</text>
				</view> 
				<view class="btn">
					<button class="btn1" type="default" size="mini">已解决</button>
					<button type="default" size="mini">未解决</button>
				</view>
			</view>
		</view>
				<view class="end">
					联系客服
				</view>
	</view>
</template>

<script>
</script>

<style>
	page{
		    background: #f2f2f2;
		    color: #666;
		    font-size: 12px;
		    line-height: 1.5;
	}
	.box{	
		max-width: 640px;
		min-height: 100%;
		margin: 0 auto;
		padding: 0;
		background-color: #ffffff;
	}
	.contain{
		padding: 1rem;
		text-align: left;
		font-size: large;
	}
	.mid{
		margin-top: 4rem;
	}
	.promlem{
		text-align: center;
		font-size: .7rem;
		    color: #9c9c9c;
	}
	.btn{
		margin-top: 1rem;
		padding-bottom: 1rem;
		text-align: center;
		border-radius: 30%;
	}
	.btn1{
		margin-right: 2rem;
	}
	.end{
		font-size: large;
	    position: fixed;
	    bottom: 0;
	    left: 0;
	    width: 100%;
	    line-height: 2rem;
	    background-color: #fff;
		display: flex;
		justify-content: center;
		 box-shadow: 0 -0.01rem 0.03rem rgba(0,0,0,.1);
		 height: 2rem;
	}
	
</style>
