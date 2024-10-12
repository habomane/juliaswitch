<script>
	import General from '../components/buttons/General.svelte';
	import Success from '../components/buttons/Success.svelte';
	import LargeHeader from '../components/typography/LargeHeader.svelte';
	import juliaoconner from '$lib/images/juliaoconner.png'
	import LargeImage from '../components/images/LargeImage.svelte';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<LargeHeader>Julia</LargeHeader>
	<LargeImage src={juliaoconner} caption="Portrait of Julia O'Conner." />
	<div class="home-btn">
		<General href="/chat/start">Start Chat</General>
		<Success href="/chat">Previous Chats</Success>
	</div>

</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	.home-btn {
		display: flex;
		justify-content: space-around;
		width: 100%;
	}
</style>
