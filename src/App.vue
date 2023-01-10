<template>
	<div class="app-vue">
		{{ welcome }}
		<br />
		<router-link to="/home">home</router-link>
		&nbsp;&nbsp;
		<router-link to="/about">about</router-link>
		<router-view></router-view>
	</div>
</template>

<script>
export default {
	data() {
		return {
			welcome: 'hi,vue3.X',
		}
	},
}
</script>

<style></style>
