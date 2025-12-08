<script>
	import { resolve } from '$app/paths';
</script>

<div class="py-15 bg-neutral-50 flex flex-col items-center space-y-15" id="works">
	<div class="flex flex-col items-center justify-center space-y-5">
		<h1 class="text-4xl text-neutral-900 text-center">Najdôležitejšie diela</h1>
		<p class="text-xl text-neutral-600 text-center">Významné literárne a jazykové príspevky</p>
	</div>

	<div class="grid md:grid-cols-2 gap-10 px-10">
		<div class="p-8 flex space-y-3 flex-col bg-white rounded-lg border border-neutral-200 h-full">
			<div class="flex space-y-0.5 flex-col">
				<h3 class="text-xl text-neutral-900">
					Dissertatio philologico-critica de literis Slavorum <br /> (Anton Bernolák)
				</h3>
			</div>

			<p class="text-neutral-600">
				Toto dielo je jazykovedno-kritická rozprava o slovenských písmenách, kde Bernolák vysvetľuje
				princípy, podľa ktorých by mala byť vytvorená spisovná slovenčina.
			</p>

			<a
				class="text-neutral-700 hover:text-neutral-900 text-sm flex flex-row items-center cursor-pointer"
				href={resolve('/diela') + '#dissertatio'}
				rel="external"
				>Zisti viac<svg
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

		<div
			class="p-8 flex space-y-3 flex-col bg-white rounded-lg border border-neutral-200 h-full justify-between"
		>
			<div class="flex space-y-0.5 flex-col">
				<h3 class="text-xl text-neutral-900">
					Slowár Slowenskí Češko-Laťinsko-Ňemecko-Uherskí <br /> (Anton Bernolák)
				</h3>
			</div>

			<p class="text-neutral-600">
				Tento šesťzväzkový slovník je najrozsiahlejším dielom Antona Bernoláka, ktorý zhŕňa slovnú
				zásobu novej normy (bernolákovčiny) a porovnáva slovenské slová s českými, latinskými,
				nemeckými a maďarskými.
			</p>

			<a
				class="text-neutral-700 hover:text-neutral-900 text-sm flex flex-row items-center cursor-pointer"
				href={resolve('/diela') + '#slovar'}
				rel="external"
				>Zisti viac<svg
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

		<div
			class="p-8 flex space-y-3 flex-col bg-white rounded-lg border border-neutral-200 h-full justify-between"
		>
			<div class="flex space-y-0.5 flex-col">
				<h3 class="text-xl text-neutral-900">
					Piľní domajší a poľní hospodár <br /> (Juraj Fándly)
				</h3>
			</div>

			<p class="text-neutral-600">
				Praktická príručka pre roľníkov a domácnosti, ktorá radí, ako efektívne spravovať farmu,
				polia, záhrady a hospodárstvo.
			</p>

			<a
				class="text-neutral-700 hover:text-neutral-900 text-sm flex flex-row items-center cursor-pointer"
				href={resolve('/diela') + '#pilni'}
				rel="external"
				>Zisti viac<svg
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

		<div
			class="p-8 flex space-y-3 flex-col bg-white rounded-lg border border-neutral-200 h-full justify-between"
		>
			<div class="flex space-y-0.5 flex-col">
				<h3 class="text-xl text-neutral-900">Svatopluk <br /> (Ján Hollý)</h3>
			</div>

			<p class="text-neutral-600">
				Epos zachytáva boj Slovákov (Slovanov) s Nemcami v období Veľkej Moravy. lavnou postavou je
				Svätopluk, ktorý prechádza vnútorným konfliktom: spočiatku spolupracuje s nepriateľmi, no
				nakoniec sa pridá k vlastnému ľudu a vedie ho k víťazstvu.
			</p>

			<a
				class="text-neutral-700 hover:text-neutral-900 text-sm flex flex-row items-center cursor-pointer"
				href={resolve('/diela') + '#svatopluk'}
				rel="external"
				>Zisti viac<svg
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
