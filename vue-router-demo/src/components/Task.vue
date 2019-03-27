<template>
	<div class="container">
		<div class="side-bar">
			<router-link to="/my_task">我的任务</router-link>
			<router-link to="/new_task">最新任务</router-link>
			<router-link to="/finish_task">已结束任务</router-link>
		</div>
		<div class="content"><router-view /></div>
	</div>
</template>

<script>
export default {
	name: 'Task',
	data() {
		return {
			
		};
	}
};
</script>

<style scoped>
	
</style>