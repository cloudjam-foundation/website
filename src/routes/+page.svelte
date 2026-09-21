<script lang="ts">
	import Logo from '$lib/components/Logo.svelte';
</script>

<svelte:head>
	<title>CloudJam</title>
	<meta name="description" content="CTF for DevOps Engineers" />
	<meta property="og:description" content="CTF for DevOps Engineers" />
	<link rel="canonical" href="https://cloudjam.org" />
	<meta property="og:title" content="CloudJam" />
	<meta property="og:type" content="website" />
	<meta property="og:image" content="https://cloudjam.org/favicon.svg" />
</svelte:head>

<div class="flex flex-row justify-between items-start w-full">
	<h1
		class="p-2 mr-auto h-80 text-6xl font-thin tracking-wider sm:text-8xl lg:text-9xl [writing-mode:sideways-rl] sm:h-[700px]"
	>
		<span class="font-light">T</span><span class="">he</span><br />
		<span class="font-light">C</span><span class="">loudJam</span><br />
		<span class="font-light">F</span><span class="">oundation</span><br />
	</h1>
	<div class="w-full sm:w-4/5 max-h-[750px]">
		<a
			href="https://github.com/cloudjam-foundation"
			class="z-50 text-4xl font-thin transition-all cursor-pointer sm:text-6xl lg:text-8xl hover:font-light mt-[2000px] text-end"
		>
			Get Involved
		</a>
		<Logo class="w-4/5 max-h-[700px]" />
	</div>
</div>

<h2 class="p-2 text-6xl font-thin tracking-wider sm:text-8xl lg:text-[10rem]">
	Building the future of<br />
	<span class="font-light text-indigo-900">DevOps</span> CTFs
</h2>
