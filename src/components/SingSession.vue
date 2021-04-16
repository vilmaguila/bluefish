<template>
	<md-card md-with-hover>
		<md-card-header>
			<div class="md-title">{{ title }}</div>
		</md-card-header>

		<md-card-content>
			{{ desc }}<br />
			{{ time }}<br />
			{{ place }}
		</md-card-content>
	</md-card>
</template>

<script>
export default {
	name: "SingSession",
	props: ["title", "desc", "time", "place"],
};
</script>