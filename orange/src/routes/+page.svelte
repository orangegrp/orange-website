<script>
	import discord_icon from '$lib/images/discord-mark-white.svg';
	import SectionOne from './components/Section1.svelte';
	import SectionTwo from './components/Section2.svelte';
</script>
  
<svelte:head>
	<title>orange🟠</title>
	<meta name="description" content="orange🟠 is 332's new ecosystem for web applications and Discord bots. The ecosystem consists of many services, apps and modules that all work together to provide a good experience both for the user and the developers maintaining the project." />
</svelte:head>

<div>
	<section class="2xl:pl-32 2xl:pr-32 md:pl-8 md:pr-8 sm:pl-4 sm:pr-4 mt-20">
		<div class="flex justify-center">
			<div class="inline-block p-2 pl-3 pr-3 border border-orange-950 rounded-lg card mb-12">
				<p class="k-light text-xs text-center">
					Hey there! Thanks for checking out orange🟠! If you're interested in helping out, please ping Alexei or Topias in #general or #tech.
				</p>	
			</div>	
		</div>

		<div>
			<h1 class="k-light text-4xl md:text-5xl font-bold leading-normal md:leading-normal text-center xl:pl-32 xl:pr-32 2xl:pl-64 2xl:pr-64">
				Welcome to project
				<span class="k-bold bg-gradient-to-r from-orange-400 to-orange-500 inline-block text-transparent bg-clip-text">
					orange🟠
				</span>.
			</h1>
			<p class="k-light text-xl mt-4 font-bold leading-normal md:leading-normal text-center xl:pl-32 xl:pr-32 2xl:pl-64 2xl:pr-64">
				<span class="k-bold bg-gradient-to-r from-orange-400 to-orange-500 inline-block text-transparent bg-clip-text">
					orange🟠
				</span> 
				is 332's new ecosystem for web applications and Discord bots.
			</p>
		</div>
	</section>
	<section class="md:pl-8 md:pr-8 sm:pl-4 sm:pr-4 mt-40">
		<div class="flex justify-center">
			<SectionOne/>		
		</div>
		<div class="flex justify-center" id="faq">
			<SectionTwo/>		
		</div>
	</section>
</div>