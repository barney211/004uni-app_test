<template>
	<view class="content">
		<grid :data="gridList"></grid>
	</view>
</template>

<script>
	import grid from '@/components/uni-grid.vue'
	export default {
		data() {
			return {
				title: 'Hello',
				gridList:[
					{image:'https://img-cdn-qiniu.dcloud.net.cn/img/shu.png',text:'圣诞树'},
    {image:'https://img-cdn-qiniu.dcloud.net.cn/img/lindang.png',text:'铃铛'},
    {image:'https://img-cdn-qiniu.dcloud.net.cn/img/laoren.png',text:'圣诞老人'},
    {image:'https://img-cdn-qiniu.dcloud.net.cn/img/liwu.png',text:'礼物'},
    {image:'https://img-cdn-qiniu.dcloud.net.cn/img/maozi.png',text:'帽子'},
    {image:'https://img-cdn-qiniu.dcloud.net.cn/img/shoutao.png',text:'手套'},
    {image:'https://img-cdn-qiniu.dcloud.net.cn/img/xueqiao.png',text:'雪橇'},
    {image:'https://img-cdn-qiniu.dcloud.net.cn/img/xunlu.png',text:'驯鹿'},
    {image:'https://img-cdn-qiniu.dcloud.net.cn/img/xuehua.png',text:'雪花'}
				]
			}
		},
		onLoad() {

		},
		components:{
			grid
		},
		methods: {

		}
	}
</script>

<style>
	.content {
		text-align: center;
		height: 400upx;
	}
</style>
