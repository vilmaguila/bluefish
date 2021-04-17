<template>
	<md-card md-with-hover>
		<md-card-header>
			<div class="md-title">{{ title }}</div>
		</md-card-header>

		<md-card-content>
			<li>{{ desc }}</li>
			<li>{{ time }}</li>
			<li>{{ place }}</li>
		</md-card-content>
	</md-card>
</template>

<script>
export default {
	name: "SingSession",
	props: ["title", "desc", "time", "place"],
};
</script>

<style scoped>
  .md-card {
    width: 320px;
    margin: 4px;
    display: inline-block;
    vertical-align: top;
  }
</style>