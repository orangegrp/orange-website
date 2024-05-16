<script>
	import logo_3d from "$lib/images/orange-logo-w-3d.png";``
</script>
  
<svelte:head>
	<title>orange🟠</title>
	<meta name="description" content="Good things are coming soon🟠." />
</svelte:head>

<div>
	<section class="2xl:pl-32 2xl:pr-32 md:pl-8 md:pr-8 sm:pl-4 sm:pr-4 mt-20">
		<div class="flex flex-col items-center w-full">
			<img src={logo_3d} width="300" height="300" alt="logo"/>
			<h1 class="text-4xl md:text-5xl font-bold leading-normal md:leading-normal text-center xl:pl-32 xl:pr-32 2xl:pl-64 2xl:pr-64">
				Hello! We're
				<span class="bg-gradient-to-r from-orange-400 to-orange-500 inline-block text-transparent bg-clip-text">
					orange🟠
				</span>.
			</h1>
			<p class="text-xl mt-4 font-bold leading-normal md:leading-normal text-center xl:pl-32 xl:pr-32 2xl:pl-64 2xl:pr-64">
				Thanks for stopping by our website. We'll be adding more stuff soon!
			</p>
		</div>
	</section>
</div>