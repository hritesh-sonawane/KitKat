<script>
	let title = 'Demon Slayer Corps Guide';

	const updateTitle = () => {
	    title = 'Nezuko chan🥰';
	};
</script>

<div class="index">
	<h2>{title}</h2>
	<p>Zombie ipsum reversus ab viral inferno, nam rick grimes malum cerebro.</p>

	<button on:click={updateTitle}>Zenitsu</button>
	<input type="text" bind:value={title} />
	<a href="/guides">View Guides</a>
	<a href="/about">About</a>
</div>

<style>
	.index {
		text-align: center;
		display: block;
		margin: 20px auto;
	}
</style>
