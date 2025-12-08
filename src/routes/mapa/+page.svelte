<script lang="ts">
	import Menu from '$lib/Components/Menu.svelte';
	import { MapLibre, DefaultMarker, Popup } from 'svelte-maplibre';

	const markers: Array<{
		lngLat: [number, number];
		label: string;
		name: string;
	}> = [
		{
			lngLat: [17.58723, 48.37741],
			label: 'TN',
			name: 'Slovenské učené tovarišstvo'
		},
		{
			lngLat: [19.51769977575174, 49.39789827706012],
			label: '',
			name: 'Anton Bernolák - rodisko'
		},
		{
			lngLat: [17.357553305331376, 48.39951136209721],
			label: '',
			name: 'Juraj Fándly - rodisko'
		},
		{
			lngLat: [17.2123732653765, 48.62907140271441],
			label: '',
			name: 'Ján Hollý - rodisko'
		},
		{
			lngLat: [20.940884320060032, 48.92763805120492],
			label: '',
			name: 'Juraj Palkovič - rodisko'
		},
		{
			lngLat: [19.43651360588298, 49.388723427674904],
			label: '',
			name: 'Martin Hamuljak - rodisko'
		},
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
