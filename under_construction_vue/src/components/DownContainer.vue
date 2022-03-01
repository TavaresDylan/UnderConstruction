<script setup>
import { ref } from "vue";
</script>

<template>
	<div id="test">
		<div id="container-bas">
			<h1>DT <small>Développeur Web</small></h1>
		</div>
	</div>
</template>

<style lang="scss">
#container-bas {
	height: 50vh;
	overflow: hidden;
	background: url(https://cdn.pixabay.com/photo/2016/11/18/00/32/programming-1833058_960_720.png);
	background-repeat: no-repeat;
	background-size: cover;
	-webkit-filter: grayscale(100%) brightness(120%) sepia(90%) hue-rotate(5deg) saturate(500%) contrast(0.7);
    filter: grayscale(100%) brightness(120%) sepia(90%) hue-rotate(5deg) saturate(500%) contrast(0.7);

}
</style>
