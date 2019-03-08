<template>
	<view class="content">
		 <map style="width: 100%; height: 300px;" :latitude="latitude" :longitude="longitude" :markers="covers">
         </map>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				latitude: 39.909,
                longitude: 116.39742,
            covers: [{
                latitude: 39.909,
                longitude: 116.39742,
                iconPath: '../../../static/location.png'
            }, {
                latitude: 39.90,
                longitude: 116.39,
                iconPath: '../../../static/location.png'
            }]
			}
		},
		onLoad() {

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
