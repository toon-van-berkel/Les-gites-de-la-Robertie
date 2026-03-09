<script lang="ts">
	import { base } from '$app/paths';
	import logo from '$lib/assets/les-gites-de-la-robertie_Clean_no-background.png';
	import '$lib/styles/style.css';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={logo} />
	<title>Les gîtes de la Robertie</title>
</svelte:head>

<div class="page">
    <header class="nav-container">
		<div class="nav-container__brand">
			<div class="nav-container__brand-mark">
				<img
					class="nav-container__brand-mark__image"
					src="{base}/les-gites-de-la-robertie_Clean_no-background.png" 
					alt="les gites de la robertie Clean no background"
				>
			</div>
			<div class="nav-container__brand-text">Les gîtes de la Robertie</div>
		</div>
		<nav class="nav-container__nav">
			<a class="nav-container__nav__item" href="{base}/">Home</a>
			<a class="nav-container__nav__item" href="{base}/">The Gîtes</a>
			<a class="nav-container__nav__item" href="{base}/">Experience</a>
			<a class="nav-container__nav__item" href="{base}/">Gallery</a>
			<a class="nav-container__nav__item" href="{base}/">Contact</a>
		</nav>
    </header>
	{@render children()}
    <footer>
		Powered by - <a href="https://www.toonvb.com" target="_blank">Toonvb.com</a> & vox-host
    </footer>
</div>
