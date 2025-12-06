<script lang="ts">
	import Menu from '$lib/Components/Menu.svelte';
	import { MapLibre, DefaultMarker, Popup } from 'svelte-maplibre';

	const markers: Array<{
		lngLat: [number, number];
		label: string;
		name: string;
	}> = [
		{
			lngLat: [19.1535, 48.7395],
			label: 'BB',
			name: 'Banska Bystrica'
		}
	];
</script>

<Menu></Menu>

<main class="flex justify-center items-center w-full h-screen z-0">
	<MapLibre
		center={[19.488957665029417, 48.76732833163731]}
		zoom={7.5}
		class="w-full h-full z-0"
		standardControls
		style="https://basemaps.cartocdn.com/gl/positron-gl-style/style.json"
	>
		{#each markers as { lngLat, name }}
			<DefaultMarker {lngLat}>
				<Popup offset={[0, -10]}>
					<div class="text-lg font-bold">{name}</div>
				</Popup>
			</DefaultMarker>
		{/each}
	</MapLibre>
</main>
