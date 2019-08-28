<template>
	<view class="container">
		<status-bar
				background-color="blue"
				bar-style="light-content"
		/>
		<text-input
			v-model="message"
		/>
		<text class="text-color-primary">{{message}}</text>
		<button
				:title="btnText"
				color="#841584"
				accessibility-label="Learn more about this purple button"
		/>
	</view>
</template>
<script>
	export default{
		data: function(){
			return {
				message: 'Hola mundob2',
				btnText: 'Soy un botón'
			}
		}
	}
</script>
<style>
.container {
	background-color: green;
	align-items: center;
	justify-content: center;
	flex: 1;
}
.text-color-primary {
	color: blue;
}
</style>
