<template>
	 <view >
		<view class="head">
			常见问题
	</view>	
		<uni-list>
				<uni-list-item @click="goDetail()" v-for="(item,title) in problemList" ></uni-list-item>
		</uni-list>
	 </view>

</template>

<script>
	import uniList from "@/components/uni-list/uni-list.vue"
	import uniListItem from "@/components/uni-list-item/uni-list-item.vue"
	export default {
	    components: {uniList,uniListItem},
		data()
		{
			return{
				problemList:[],
			}
		},
		onLoad() {
			this.problemList()
		},
		}
		
		methods:{
			goDetail ()
			{
				uni.request({
					url: '118.24.96.51:8080//problem/asd/asd', 
					data:{
						text:'uni.request'
					},
					success: (res) => {
					console.log(res)
					this.problemList=res.data
					console.log(this.problemList)
				}
				});
							
							
				uni.navigateTo({
					url:'goodstime?id=4'
				})
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
