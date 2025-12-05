<script lang="ts">
	import Heading from '$lib/Components/Heading.svelte';
	import Introduction from '$lib/Components/Introduction.svelte';
</script>

<meta name="viewport" content="width=device-width, initial-scale=1.0" />

<header
	class="sticky top-0 flex flex-row justify-between border-b border-neutral-200 bg-white items-center h-16"
>
	<div class="flex space-x-2 items-center px-5">
		<svg
			class="w-7 h-7 text-neutral-800 text-2xl"
			aria-hidden="true"
			xmlns="http://www.w3.org/2000/svg"
			width="24"
			height="24"
			fill=""
			viewBox="0 0 24 24"
		>
			<path
				fill-rule="evenodd"
				d="M6 2a2 2 0 0 0-2 2v15a3 3 0 0 0 3 3h12a1 1 0 1 0 0-2h-2v-2h2a1 1 0 0 0 1-1V4a2 2 0 0 0-2-2h-8v16h5v2H7a1 1 0 1 1 0-2h1V2H6Z"
				clip-rule="evenodd"
			/>
		</svg>

		<h3 class="text-2xl text-neutral-900">Bernolákovci</h3>
	</div>

	<nav class="p-4 flex space-x-8 items-center lg:flex hidden">
		<a class=" text-lg text-neutral-600 hover:text-neutral-900 text-nowrap" href="">Úvod</a>
		<a class=" text-lg text-neutral-600 hover:text-neutral-900 text-nowrap" href=""
			>Kľúčové osobnosti</a
		>
		<a class=" text-lg text-neutral-600 hover:text-neutral-900 text-nowrap" href=""
			>Chronologická os</a
		>
		<a class=" text-lg text-neutral-600 hover:text-neutral-900 text-nowrap" href="">Diela</a>
		<a class=" text-lg text-neutral-600 hover:text-neutral-900 text-nowrap" href="">Jazyk</a>
		<a class=" text-lg text-neutral-600 hover:text-neutral-900 text-nowrap" href="">Mapa</a>
		<a class=" text-lg text-neutral-600 hover:text-neutral-900 text-nowrap" href="">Galéria</a>
	</nav>

	<div class="lg:hidden px-5">
		<svg
			class="w-10 h-10 text-gray-800"
			aria-hidden="true"
			xmlns="http://www.w3.org/2000/svg"
			width="24"
			height="24"
			fill="none"
			viewBox="0 0 24 24"
		>
			<path
				stroke="currentColor"
				stroke-linecap="round"
				stroke-width="2"
				d="M5 7h14M5 12h14M5 17h14"
			/>
		</svg>
	</div>
</header>

<Heading />

<Introduction />
