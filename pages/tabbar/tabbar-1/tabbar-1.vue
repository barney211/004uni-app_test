<template>
	<view class="content">
        <carosoul></carosoul>
	
		页面 - 1
	</view>
</template>

<script>
import carosoul from "@/components/jing-swiper.vue"	
export default {
	data() {
		return {
			title: 'Hello'
		};
	},
	components:{
		carosoul
	},
	onLoad() {},
	methods: {}
};
</script>

<style>
.content {
	text-align: center;
	height: 400upx;
}
</style>
