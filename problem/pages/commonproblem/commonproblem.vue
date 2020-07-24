<template>
	 <view >
		<view class="head">
			问题类型
	</view>	
		<uni-list>
		    <uni-list-item @click="goDetail()" title="标题文字"></uni-list-item>
		</uni-list>
	 </view>
	</view>

</template>

				
<script>
	import uniList from "@/components/uni-list/uni-list.vue"
	import uniListItem from "@/components/uni-list-item/uni-list-item.vue"
	export default {
	    components: {uniList,uniListItem},
		
		data() {
			return {
				
			}
		},
		
		methods:{
			goDetail ()
			{
				uni.navigateTo({
					url:'timeproblem?id=3'
				})
			}
		}
	}
</script>

<style>
	page{
		background-color: #eee;
	}
	.head{
		height: 2rem;
		line-height: 2rem;
	}

</style>