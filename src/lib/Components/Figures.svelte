<script lang="ts">
	import { asset, resolve } from '$app/paths';
</script>

<div class="flex items-center flex-col py-15 bg-neutral-50" id="figures">
	<div class="flex flex-col space-y-5 items-center">
		<h1 class="text-4xl text-neutral-900">Predstavitelia</h1>
		<p class="text-xl text-neutral-600 text-center">
			Priekopníci, ktorí formovali slovenský spisovný jazyk
		</p>
	</div>

	<!-- TODO: Center images -->
	<div class="flex flex-row items-center justify-center flex-wrap">
		<div class="flex flex-col items-center space-y-3 pt-15 px-18">
			<img
				src={asset('/anton_bernolak.webp')}
				alt=""
				class="w-24 h-24 rounded-full border-2 border-neutral-200"
			/>
			<h3 class="text-lg text-neutral-900">Anton Bernolák</h3>
			<p class="text-sm text-neutral-600">Kodifikátor Slovenčiny</p>
			<a
				class="text-neutral-700 hover:text-neutral-900 text-sm flex flex-row items-center cursor-pointer"
				href={resolve('/predstavitelia') + '#bernolak'}
				rel="external"
				>Pozri Profil <svg
					class="w-5 h-5"
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
						stroke-linejoin="round"
						stroke-width="2"
						d="M19 12H5m14 0-4 4m4-4-4-4"
					/>
				</svg>
			</a>
		</div>

		<div class="flex flex-col items-center space-y-3 pt-15 px-18">
			<img
				src={asset('/anton_bernolak.webp')}
				alt=""
				class="w-24 h-24 rounded-full border-2 border-neutral-200"
			/>
			<h3 class="text-lg text-neutral-900">Juraj Fándly</h3>
			<p class="text-sm text-neutral-600">Osvietenský spisovateľ</p>
			<a
				class="text-neutral-700 hover:text-neutral-900 text-sm flex flex-row items-center cursor-pointer"
				href={resolve('/predstavitelia') + '#fandly'}
				rel="external"
				>Pozri Profil <svg
					class="w-5 h-5"
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
						stroke-linejoin="round"
						stroke-width="2"
						d="M19 12H5m14 0-4 4m4-4-4-4"
					/>
				</svg>
			</a>
		</div>

		<div class="flex flex-col items-center space-y-3 pt-15 px-18">
			<img
				src={asset('/anton_bernolak.webp')}
				alt=""
				class="w-24 h-24 rounded-full border-2 border-neutral-200"
			/>
			<h3 class="text-lg text-neutral-900">Ján Hollý</h3>
			<p class="text-sm text-neutral-600">Národný básnik</p>
			<a
				class="text-neutral-700 hover:text-neutral-900 text-sm flex flex-row items-center cursor-pointer"
				href={resolve('/predstavitelia') + '#holly'}
				rel="external"
				>Pozri Profil <svg
					class="w-5 h-5"
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
						stroke-linejoin="round"
						stroke-width="2"
						d="M19 12H5m14 0-4 4m4-4-4-4"
					/>
				</svg>
			</a>
		</div>

		<div class="flex flex-col items-center space-y-3 pt-15 px-18">
			<img
				src={asset('/anton_bernolak.webp')}
				alt=""
				class="w-24 h-24 rounded-full border-2 border-neutral-200"
			/>
			<h3 class="text-lg text-neutral-900">Martin Hamuljak</h3>
			<p class="text-sm text-neutral-600">Kultúrny organizátor</p>
			<a
				class="text-neutral-700 hover:text-neutral-900 text-sm flex flex-row items-center cursor-pointer"
				href={resolve('/predstavitelia') + '#hamuljak'}
				rel="external"
				>Pozri Profil <svg
					class="w-5 h-5"
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
						stroke-linejoin="round"
						stroke-width="2"
						d="M19 12H5m14 0-4 4m4-4-4-4"
					/>
				</svg>
			</a>
		</div>

		<div class="flex flex-col items-center space-y-3 pt-15 px-18">
			<img
				src={asset('/anton_bernolak.webp')}
				alt=""
				class="w-24 h-24 rounded-full border-2 border-neutral-200"
			/>
			<h3 class="text-lg text-neutral-900">Juraj Palkovič</h3>
			<p class="text-sm text-neutral-600">Literárny propagátor</p>
			<a
				class="text-neutral-700 hover:text-neutral-900 text-sm flex flex-row items-center cursor-pointer"
				href={resolve('/predstavitelia') + '#palkovic'}
				rel="external"
				>Pozri Profil <svg
					class="w-5 h-5"
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
						stroke-linejoin="round"
						stroke-width="2"
						d="M19 12H5m14 0-4 4m4-4-4-4"
					/>
				</svg>
			</a>
		</div>
	</div>
</div>
