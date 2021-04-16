<template>
	<div id="app">
		<md-tabs md-sync-route>
			<md-tab id="tab-home" md-label="Home" to="/" exact> </md-tab>
			<md-tab id="tab-sessions" md-label="Sessions" to="/sessions" exact>
			</md-tab>
			<md-tab id="tab-about" md-label="About" to="/about" exact> </md-tab>
		</md-tabs>

		<router-view />
	</div>
</template>