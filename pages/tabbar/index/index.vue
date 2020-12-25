<template>
	<view class="content">
		<!-- 自定义导航栏 -->
		<navbar></navbar>
		<view v-for="item in 100">
			{{item}} 内容那个
		</view>
	</view>
</template>

<script>
	// easyCom components/组件名/组件名.vue 局部引入
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style lang="scss">
	
</style>
