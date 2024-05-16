<script>
	import { onMount } from "svelte";
	import icon from "$lib/images/orange-logo-w.svg";
	import discord_icon from "$lib/images/discord-mark-white.svg";

	onMount(() => {
		const button = document.querySelector("#nav-menu-button");
		const menu = document.querySelector("#nav-menu");

		if (button !== null && menu !== null) {
			button.addEventListener("click", () => {
				menu.classList.toggle("hidden");
			});
		}
	});
</script>

<header class="sticky top-0">
	<nav
		class="lg:pl-16 lg:pr-16 2xl:pl-64 2xl:pr-64 flex flex-wrap items-center justify-between w-full py-4 md:py-0 px-4 text-lg text-gray-100 nav-bg"
	>
		<div>
			<a href="/">
				<img src={icon} class="h-5 md:h-5 pl-4" alt="Orange Logo" />
			</a>
		</div>

		<svg
			xmlns="http://www.w3.org/2000/svg"
			id="nav-menu-button"
			class="h-6 w-6 cursor-pointer md:hidden block"
			fill="none"
			viewBox="0 0 24 24"
			stroke="currentColor"
		>
			<path
				stroke-linecap="round"
				stroke-linejoin="round"
				stroke-width="2"
				d="M4 6h16M4 12h16M4 18h16"
			/>
		</svg>

		<div
			class="hidden w-full md:flex md:items-center md:w-auto"
			id="nav-menu"
		>
			<ul
				class="pt-4 text-base text-grau-100 md:flex md:justify-between md:pt-0"
			>
				<li>
					<a
						class="my-3 mx-4 block text-sm"
						href="https://dash.orange.order332.com/login"
					>
						<div
							class="flex flex-row justify-between gap-x-2 items-center bg-gradient-to-r from-orange-500 to-orange-600 p-1 rounded-lg px-4 hover:from-orange-400 hover:to-orange-500 shadow-lg shadow-orange-950 hover:shadow-orange-900"
						>
							Dash Login
							<svg
								xmlns="http://www.w3.org/2000/svg"
								fill="none"
								viewBox="0 0 24 24"
								stroke-width="1.5"
								stroke="currentColor"
								class="w-6 h-6"
							>
								<path
									stroke-linecap="round"
									stroke-linejoin="round"
									d="M17.25 8.25 21 12m0 0-3.75 3.75M21 12H3"
								/>
							</svg>
						</div>
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
