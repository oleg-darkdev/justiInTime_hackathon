<script>
	const steps = [
		{
			title: 'Zbieranie informacji',
			desc: [
				'Autonomiczne zbieranie, łączenie i kontekstualizacja danych od operatorów w zakładzie'
			]
		},
		{
			title: 'Przejrzystość i dostępność',
			desc: [
				'Bezpieczny dostęp do kompletnych, użytecznych danych w czasie rzeczywistym - za pośrednictwem przyjaznej dla urządzeń mobilnych, opartej na chmurze aplikacji, z wykorzystaniem niezależnych serwisów'
			]
		},
		{
			title: 'Wizualizacja systemu produkcyjnego',
			desc: [
				'Wydajne wizualizacje danych na hali produkcyjnej umożliwiają zespołowi szybkie i terminowe wykonywanie zadań zgodnie z dokumentacją'
			]
		},
		{
			title: 'Analiza oparta na metrykach Kanban',
			desc: [
				'Przeprowadzaj dogłębną analizę danych historycznych i w czasie rzeczywistym z ogromną dokładności'
			]
		},
		{
			title: 'Optymalizacja i rozwój',
			desc: [
				'Analiza danych produkcyjnych pomaga zidentyfikować strategie poprawy wydajności i zmierzyć wpływ wszelkich zmian w procesie'
			]
		},
		{
			title: 'Przemysł 4.0',
			desc: [
				'Czwarta rewolucja przemysłowa (Przemysł 4.0) obejmuje nowe podejście do produkcji oparte na masowym wdrażaniu technologii informatycznych w przemyśle i cyfryzacji procesów biznesowych'
			]
		}
	];
</script>

<section class='min-h-screen'>
	<h2 class=" text-center lg:text-6xl text-4xl  font-black text-violet-700">
		Co się będzie działo <br class="hidden lg:block" /> w systemie produkcyjnym
	</h2>
	<div class="relative mx-auto w-full max-w-7xl items-center px-5 py-12 md:px-12 lg:px-24">
		<div class="mx-auto grid w-full grid-cols-1 gap-6 lg:grid-cols-3">
			{#each steps as step}
				<div class="">
					<div class="mb-3 flex items-center">
						<div
							class="mr-3 inline-flex h-12 w-12 flex-shrink-0 items-center justify-center rounded-full bg-violet-100 text-violet-600"
						>
							<svg
								xmlns="http://www.w3.org/2000/svg"
								class="icon icon-tabler icon-tabler-aperture h-6 w-6"
								width="24"
								height="24"
								viewBox="0 0 24 24"
								stroke-width="1.5"
								stroke="currentColor"
								fill="none"
								stroke-linecap="round"
								stroke-linejoin="round"
							>
								<path stroke="none" d="M0 0h24v24H0z" fill="none" />
								<circle cx="12" cy="12" r="9" />
								<line x1="3.6" y1="15" x2="14.15" y2="15" />
								<line x1="3.6" y1="15" x2="14.15" y2="15" transform="rotate(72 12 12)" />
								<line x1="3.6" y1="15" x2="14.15" y2="15" transform="rotate(144 12 12)" />
								<line x1="3.6" y1="15" x2="14.15" y2="15" transform="rotate(216 12 12)" />
								<line x1="3.6" y1="15" x2="14.15" y2="15" transform="rotate(288 12 12)" />
							</svg>
						</div>
						<h1 class="text-xl font-semibold leading-none tracking-tighter text-violet-500">
							{step.title}
						</h1>
					</div>
					{#each step.desc as desc}
						<p class="mx-auto text-base leading-relaxed text-gray-500">
							{desc}
						</p>
					{/each}
				</div>
			{/each}
		</div>
	</div>
</section>
