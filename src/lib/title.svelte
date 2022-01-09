<script>
	export let title = 'Demon Slayer Corps';
</script>

<div class="title">
	<img class="img" src="/anime-logo.png" alt="Logo" />
	<h1>{title}</h1>
</div>

<style>
	.title {
		display: flex;
	}
	.title img {
		display: inline-block;
		filter: invert(88%) sepia(18%) saturate(886%) hue-rotate(199deg) brightness(100%) contrast(90%);
	}
	.title h1 {
		margin-left: 10px;
	}
	.img {
		width: 75px;
		height: auto;
	}
</style>
