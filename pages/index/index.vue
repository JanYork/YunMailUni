<template>
	<view>
		<u-tabs :list="list" :is-scroll="false" :current="current" bar-width="50" active-color="#30B1B7"
			@change="change"></u-tabs>
	</view>
</template>

<script>
export default {
	data() {
		return {
			list: [{
				name: "所有",
			},
			{
				name: "匿名",
			},
			{
				name: "实体",
			},
			{
				name: "心愿",
			},
			{
				name: "短信",
			},
			],
			current: 0,
		}
	}
}
</script>

<style>

</style>
