<template>
	<view class="content">
		<view class="list-cell">
			<text class="cell-tit ">{{ title }}</text>
		</view>
		
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		props:{
			title: {
				type: String,
				default: '标题'
			},
			images: {
				type:'String',
				src:'地址'
				
			}
		},
		methods: {
			
		}
	}
</script>

<style>

</style>
