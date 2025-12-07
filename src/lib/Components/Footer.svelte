<script>
	import { resolve } from '$app/paths';
</script>

<footer
	class="bg-neutral-900 text-white py-12 flex flex-col md:space-x-50 space-x-0 space-y-10 px-10 md:flex-row justify-center"
>
	<div class="flex flex-row items-center md:justify-start justify-center">
		<svg
			class="w-7 h-7 text-white text-2xl"
			aria-hidden="true"
			xmlns="http://www.w3.org/2000/svg"
			width="24"
			height="24"
			fill="currentColor"
			viewBox="0 0 24 24"
		>
			<path
				fill-rule="evenodd"
				d="M6 2a2 2 0 0 0-2 2v15a3 3 0 0 0 3 3h12a1 1 0 1 0 0-2h-2v-2h2a1 1 0 0 0 1-1V4a2 2 0 0 0-2-2h-8v16h5v2H7a1 1 0 1 1 0-2h1V2H6Z"
				clip-rule="evenodd"
			/>
		</svg>
		<h3 class="text-lg">Bernolákovci</h3>
	</div>

	<div class="flex flex-col space-y-3">
		<h4 class="text-sm text-neutral-300 uppercase tracking-wider pb-3">Preskúmať</h4>
		<a href={resolve(`/`) + '#figures'} class="text-neutral-400 hover:text-white transition-colors"
			>Predstavitelia</a
		>
		<a href={resolve(`/`) + '#timeline'} class="text-neutral-400 hover:text-white transition-colors"
			>Chronologická Os</a
		>
		<a href={resolve(`/`) + '#works'} class="text-neutral-400 hover:text-white transition-colors"
			>Diela</a
		>
	</div>

	<div class="flex flex-col space-y-3">
		<h4 class="text-sm text-neutral-300 uppercase tracking-wider pb-3">Zdroje</h4>
		<a href="" class="text-neutral-400 hover:text-white transition-colors">Galéria</a>
		<a href={resolve(`/mapa`)} class="text-neutral-400 hover:text-white transition-colors">Mapa</a>
		<a href="" class="text-neutral-400 hover:text-white transition-colors">Pramene</a>
	</div>
</footer>
