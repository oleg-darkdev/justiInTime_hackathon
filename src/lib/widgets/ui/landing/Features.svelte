<script>
	const features = [
		{
			icon: '',
			title:
				'Raportowanie dla klientów o zgodności procesu z potwierdzeniem niezależnym od niezależnych serwisów E-czas i Trello',
			description: ''
		},
		{
			icon: '',
			title:
				'Śledzenie krytycznych wskaźników produkcji przy użyciu metryk systemów produkcyjnych kanban.',
			description: ''
		},

		{
			icon: '',
			title: 'Pomaga analizować i redukować wąskie gardła w systemie produkcyjnym.',
			description: ''
		},
		// {
		// 	icon: '',
		// 	title: 'Снижение эксплуатационных расходов и простоев оборудования включенным',
		// 	description: ''
		// },
		{
			icon: '',
			title: 'Standaryzacja miejsca pracy z możliwością symulacji procesów przed rozpoczęciem pracy.',
			description: ''
		}
	];
</script>

<section class="mx-auto flex min-h-screen items-center justify-center md:px-6">
	<div class="flex flex-wrap">
		<div class="mb-6 w-full shrink-0 grow-0 basis-auto px-3 lg:mb-0 lg:w-4/12">
			<p class="text-primary-400 mb-6 font-bold uppercase ">Features</p>
			<h2 class="mb-6 text-3xl font-bold text-violet-600">
				Dlaczego <span class="text-4xl font-black ">Just in Time</span>
			</h2>

			<p class="mb-12 text-neutral-300">
				Przejrzysty system produkcji z raportowaniem zgodności procesu z niezależną weryfikacją
				przez niezależne serwisy <span class="text-2xl font-black text-violet-600"
					>E-czas & Trello</span
				>
			</p>
		</div>

		<div
			class="mb-md-0 mb-6 w-full shrink-0 grow-0 basis-auto rounded-lg bg-violet-600 py-6 px-3 lg:w-8/12"
		>
			<div class="flex flex-wrap">
				{#each features as feature}
					<div class="mb-4 w-full shrink-0 grow-0 basis-auto lg:w-6/12 lg:px-3">
						<div class="flex">
							<div class="shrink-0" />
							<div class="ml-4 grow">
								<p class="mb-3 text-2xl font-bold text-white">{feature.title}</p>
							</div>
						</div>
					</div>
				{/each}
			</div>
		</div>
	</div>
</section>
