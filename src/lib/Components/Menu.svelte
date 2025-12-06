<script lang="ts">
	import { resolve } from '$app/paths';
	import Dropdown from './Dropdown.svelte';
</script>

<header
	class="sticky top-0 flex flex-row border-b border-neutral-200 bg-white items-center h-16 z-50 justify-center"
>
	<div class="flex flex-row w-7xl justify-between">
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

		<nav class="p-4 flex space-x-6 items-center lg:flex hidden">
			<a
				class=" text-lg text-neutral-600 hover:text-neutral-900 text-nowrap"
				href={resolve(`/`) + '#introduction'}>Úvod</a
			>
			<a
				class=" text-lg text-neutral-600 hover:text-neutral-900 text-nowrap"
				href={resolve(`/`) + '#figures'}>Kľúčové osobnosti</a
			>
			<a class=" text-lg text-neutral-600 hover:text-neutral-900 text-nowrap" href={resolve(`/`) + '#timeline'}
				>Chronologická os</a
			>
			<a class=" text-lg text-neutral-600 hover:text-neutral-900 text-nowrap" href={resolve(`/`) + '#works'}>Diela</a>
			<a class=" text-lg text-neutral-600 hover:text-neutral-900 text-nowrap" href="">Jazyk</a>
			<a
				class=" text-lg text-neutral-600 hover:text-neutral-900 text-nowrap"
				href={resolve(`/mapa`)}>Mapa</a
			>
			<a class=" text-lg text-neutral-600 hover:text-neutral-900 text-nowrap" href="">Galéria</a>
		</nav>

		<Dropdown />
	</div>
</header>
