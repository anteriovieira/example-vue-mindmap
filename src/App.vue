<template>
	<div id="app">
		<mind-map
			:nodes="nodes"
			:connections="connections"
			:editable="true"
		/>
	</div>
</template>

<script>
	import map from './map'

	console.log(map)

	export default {
    name: 'app',
		data() {
			return {...map}
		}
  }
</script>
