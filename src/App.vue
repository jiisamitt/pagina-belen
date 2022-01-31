<template>
	<div class="home-container">
		<!-- Superior Bar-->
		<div class="home-superior-bar">
			<span class="home-superior-bar-element">
				<p class="home-superior-bar-text">Inicio</p>
			</span>
			<div class="home-superior-bar-element" @click="goto('nosotros')">
				Nosotros
			</div>
			<span class="home-superior-bar-element"> <p>Cabañas</p> </span>
			<span class="home-superior-bar-element">
				<p>Preguntas frecuentes</p>
			</span>
			<span class="home-superior-bar-element">Galería</span>
			<span class="home-superior-bar-element">Contacto</span>
		</div>
		<!-- Welcome -->
		<div>
			<img
				class="home-image"
				src="../src/assets/pexels-pixabay-163756.jpg"
				alt=""
			/>
		</div>
		<div class="home-text-big">Cabañas Roble Quemado</div>
		<!-- Nosotros -->
		<div ref="nosotros"><Nosotros /></div>

		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
		<br />
	</div>
</template>

<script>
	import Nosotros from './components/Nosotros.vue';
	export default {
		name: 'App',
		components: { Nosotros },
		methods: {
			goto(refName) {
				var element = this.$refs[refName];
				var top = element.offsetTop;

				window.scrollTo({ top: top, behavior: 'smooth' });
			},
		},
	};
</script>

<style>
	#app {
		font-family: Avenir, Helvetica, Arial, sans-serif;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
		text-align: center;
		color: #2c3e50;
		margin-top: 60px;
	}
	.home-container {
		width: 100%;
		height: 100%;
	}
	.home-text-big {
		font-size: 50px;
		font-weight: bolder;
		color: white;
	}
	.home-superior-bar {
		background: rgba(48, 31, 9, 0.97);
		position: absolute;
		top: 0px;
		left: 0px;
		width: 100%;
		height: 60px;
		display: flex;
		align-items: center;
		color: rgb(240, 229, 221);
	}
	.home-superior-bar-element {
		position: relative;
		margin-left: 20px;
	}
	.home-superior-bar-element:hover {
	}
	.home-superior-bar-text {
		width: 150%;
		height: 170%;
	}
	.home-superior-bar-text:hover {
		background: rgba(97, 79, 55, 0.7);
		border-radius: 10px 10px 10px 10px;
	}
	.home-image {
		position: absolute;
		z-index: -100;
		top: 0px;
		left: 0px;
		width: 100%;
		height: 100%;
	}
</style>
