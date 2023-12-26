<script>
    import { onMount } from 'svelte';
    import icon from '$lib/images/orange-logo-w.svg';
	import discord_icon from '$lib/images/discord-mark-white.svg';

	onMount(() => {
		const button = document.querySelector('#nav-menu-button');
		const menu = document.querySelector('#nav-menu');

		if (button !== null && menu !== null) {
			button.addEventListener('click', () => {
				menu.classList.toggle('hidden');
			});
		}
	});	
</script>


<header class="sticky top-0">
	<nav class="lg:pl-16 lg:pr-16 2xl:pl-64 2xl:pr-64 flex flex-wrap items-center justify-between w-full py-4 md:py-0 px-4 text-lg text-gray-100 nav-bg">
		<div>
			<a href="/">
				<img src={icon} class="h-6 md:h-8 pl-4" alt="Sentie Logo" />
			</a>
		</div>

		<svg xmlns="http://www.w3.org/2000/svg" id="nav-menu-button" class="h-6 w-6 cursor-pointer md:hidden block" fill="none" viewBox="0 0 24 24" stroke="currentColor">
			<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/>
		</svg>
	
		<div class="hidden w-full md:flex md:items-center md:w-auto" id="nav-menu">
			<ul class="pt-4 text-base text-grau-100 md:flex md:justify-between md:pt-0">
				<li>
					<a class="m-6 py-2 block text-lg" href="/">
						orange🟠
					</a>
				</li>
				<li>
					<a class="m-6 py-2 block text-lg" href="/#faq">
						FAQ
					</a>
				</li>
			</ul>
		</div>
	</nav>
</header>

<style>
.nav-bg {
	background-color: #000000ee;
	backdrop-filter: blur(8px);
	-webkit-backdrop-filter: blur(8px);
	transition: background-color 0.3s ease; /* Smooth transition for background-color */
	border-bottom: 1px solid #ffddaa11;
	z-index: 900;
}
</style>