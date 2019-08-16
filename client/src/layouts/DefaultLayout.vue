<template>
	<b-container class="layout-default" fluid>
		<!-- Header -->
		<b-container fluid>
			<b-row align-h="between">
				<b-col cols="auto" class="p-0">
					HEADER
				</b-col>
			</b-row>
		</b-container>

		<!-- Content -->
		<b-container fluid >
			<b-row class="rb-content-page">
				<slot></slot>
			</b-row>
		</b-container>
	</b-container>
</template>

<script>
	export default {
		name: 'DefaultLayout'
	}
</script>

<style lang="scss" scoped>
</style>
