<script lang="ts">
	import { resolve } from '$app/paths';

	let open = false;

	function toggle() {
		open = !open;
	}

	function close() {
		open = false;
	}

	const items = [
		{ label: 'Úvod', href: resolve(`/`) + '#introduction' },
		{ label: 'Predstavitelia', href: resolve(`/`) + '#figures' },
		{ label: 'Chronologická os', href: resolve(`/`) + '#timeline' },
		{ label: 'Diela', href: resolve(`/`) + '#works' },
		{ label: 'Jazyk', href: resolve(`/`) + '#language' },
		{ label: 'Mapa', href: resolve(`/mapa`) },
		{ label: 'Galeria', href: resolve(`/galeria`) }
	];
</script>

<button class="lg:hidden px-5" on:click={toggle}>
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
</button>

{#if open}
	<ul
		class="fixed w-full left-0 top-16 bg-white border border-neutral-200 rounded-lg z-50"
		on:focusout={close}
	>
		{#each items as item, i}
			<li>
				{#if i % 2 == 0}
					<a
						href={item.href}
						class="block px-4 py-2 text-neutral-700 hover:bg-gray-100 bg-neutral-50"
						on:click={() => (open = false)}
					>
						{item.label}
					</a>
				{:else}
					<a
						href={item.href}
						class="block px-4 py-2 text-neutral-700 hover:bg-gray-100"
						on:click={() => (open = false)}
					>
						{item.label}
					</a>
				{/if}
			</li>
		{/each}
	</ul>
{/if}

<style>
	ul {
		animation: fadeIn 0.15s ease-in-out;
	}
	@keyframes fadeIn {
		from {
			opacity: 0;
			transform: translateY(-5px);
		}
		to {
			opacity: 1;
			transform: translateY(0);
		}
	}
</style>
