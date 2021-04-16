<template>
	<div>
		<md-toolbar>
			<h3 class="md-title">{{ title }}</h3>
		</md-toolbar>
	</div>
</template>

<script>
export default {
	name: 'TheSessionsHeader',
	props: ['title']
}
</script>