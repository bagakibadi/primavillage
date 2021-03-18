<template>
<div id="home">
    <div class="intro-section">
		<div class="overlay-bg"></div>
		<div style="width: 100%">
			<video autoplay muted loop id="myVideo" width="100%">
				<source src="/assets/video/prima3.mp4" type="video/mp4">
			</video>
		</div>
		<div class="text-intro">
			<h1 class="text1">Primavillage</h1>
			<h1 class="text2">#MajuBersamaDesa</h1>
		</div>
	</div>
</div>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style scoped>
.overlay-bg{
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	background: rgba(0, 0, 0, .15);
}
	.intro-section{
		position: relative;
	}
	.text-intro{
		position: absolute;
		text-align: center;
		width: 100%;
		top: 20%;
	}
	.text-intro h1{
		font-weight: 700;
		font-size: 3.5rem;
		color: #fff;
	}
	.text-intro .text2{
		/* color: #076825; */
	}
	@media only screen and (max-width: 600px) {
		.text-intro h1{
			font-size: 2rem;
		}
	}
</style>
