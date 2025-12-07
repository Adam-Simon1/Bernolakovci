<script lang="ts">
	import { asset } from '$app/paths';
	import Menu from '$lib/Components/Menu.svelte';

	const images = [
		{
			alt: '',
			src: asset('/anton_bernolak.webp')
		},
		{
			alt: '',
			src: asset('/fandly.jpeg')
		},
		{
			alt: '',
			src: asset('/Jan_Holly.jpg')
		},
		{
			alt: '',
			src: asset('/Juraj_Palkovic.jpg')
		},
		{
			alt: '',
			src: asset('/Martin_Hamuljak.png')
		},
		{
			alt: '',
			src: asset('/slovenske_ucene_tovarisstvo.jpg')
		}
	];
</script>

<Menu />

<div class="lg:columns-3 md:columns-2 columns-1 p-2">
	{#each images as image}
		<img class="rounded-lg w-full mb-4" src={image.src} alt={image.alt} />
	{/each}
</div>
