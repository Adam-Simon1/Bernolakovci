<script lang="ts">
	import { asset } from '$app/paths';
</script>

<div
	class="flex lg:flex-row items-center px-5 py-25 bg-neutral-50 flex-col lg:space-x-5 lg:space-y-0 space-y-10 justify-center"
>
	<div class="space-y-8 flex flex-col justify-center items-center lg:items-start">
		<h1 class="text-5xl text-neutral-900 text-center lg:text-left">Bernolákovské hnutie</h1>
		<p class="text-xl text-neutral-600 max-w-xl text-center lg:text-left">
			Objavte priekopnícke jazykové hnutie, ktoré formovalo slovenský jazyk a kultúrnu identitu na
			konci 18. a začiatku 19. storočia.
		</p>
		<div class="flex flex-row space-x-3">
			<button
				class="bg-neutral-900 text-white px-6 py-3 rounded-lg hover:bg-neutral-800 transition-colors cursor-pointer"
				>Objav históriu</button
			>
			<button
				class="border border-neutral-300 text-neutral-700 px-6 py-3 rounded-lg hover:bg-neutral-50 transition-colors cursor-pointer"
				>Chronologická os</button
			>
		</div>
	</div>
	<img
		class="lg:w-3/4 w-full rounded-lg max-w-lg"
		src={asset('/slovenske_ucene_tovarisstvo.jpg')}
		alt=""
	/>
</div>
