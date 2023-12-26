<script>
import Header from './components/Header.svelte';
import './styles.css';
import "../app.css";
import logo from '$lib/images/orange-logo-w.svg';
import icon from '$lib/images/orange-logo-w-icon.svg';
</script>

<svelte:head>
	<link rel="icon" type="image/svg" href={icon} />
	<meta property="og:image" content="{icon}" />
	<meta name="og:site_name" content="332"/>
	<meta name="og:title" content="Project orange🟠"/>
	<meta property="og:type" content="website" />
	<meta property="og:url" content="https://orange.order332.com" />
	<meta property="og:description" content="orange🟠 is 332's new ecosystem for web applications and Discord bots. The ecosystem consists of many services, apps and modules that all work together to provide a good experience both for the user and the developers maintaining the project."/>
</svelte:head>

<div class="app">
	<div class="night-sky-box">
		<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 50" width="100%" height="100%">
			<rect width="100%" height="100%" fill="transparent" />
			{#each Array(200) as _, i}
				<circle cx={(i * 2) + Math.random() * 2} cy={(Math.random() * 30) + 5} r={Math.random() * 0.125} fill="white" />
			{/each}
		</svg>	
	</div>
	<Header />
	<main>
		<slot />
	</main>
	<footer class="rounded-lg shadow mt-24">
		<div class="w-full max-w-screen-xl mx-auto p-4 md:py-8">
			<div class="sm:flex sm:items-center sm:justify-between">
				<a href="/" class="flex items-center mb-4 sm:mb-0">
					<img src={logo} class="h-6 mr-3" alt="Sentie Logo" />
					<span class="self-center text-xl font-semibold whitespace-nowrap"></span>
				</a>
				<ul class="flex flex-wrap items-center mb-6 text-sm font-medium sm:mb-0">
					<li>
						<a href="/privacy-policy" class="mr-4 hover:underline md:mr-6">Privacy Policy</a>
					</li>
					<li>
						<a href="/terms-of-service" class="mr-4 hover:underline md:mr-6 ">Terms of Service</a>
					</li>
				</ul>
			</div>
			<hr class="my-6 border-zinc-800 sm:mx-auto lg:my-8" />
			<span class="block text-sm text-zinc-500 sm:text-center">© 2024 orange🟠 by 332</span>
		</div>
	</footer>

</div>

<style>
.app {
	display: flex;
	flex-direction: column;
	min-height: 100vh;
	
}

main {
	flex: 1;
	flex-direction: column;
	padding: 1rem;
	margin: 0;
	box-sizing: border-box;
}

.night-sky-box {
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	max-height: 1500px; /* Ensure it covers the entire viewport */
	z-index: -999;
}

footer {
	background-color: #0f0a05ee;
	backdrop-filter: blur(8px);
	-webkit-backdrop-filter: blur(8px);
	transition: background-color 0.3s ease; /* Smooth transition for background-color */
	border: 1px solid #ffdaaa11;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}
</style>
