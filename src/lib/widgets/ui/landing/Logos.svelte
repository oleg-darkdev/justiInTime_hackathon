<script>
	const logos = [
		{
			img: 'amazon.svg',
			link: '',
			title: ''
		},
		{
			img: 'intel.svg',
			link: '',
			title: ''
		},
		{
			img: 'jonn.svg',
			link: '',
			title: ''
		},
		{
			img: 'infineon.svg',
			link: '',
			title: ''
		},
		{
			img: 'nxp.svg',
			link: '',
			title: ''
		},
		{
			img: 'samsung.svg',
			link: '',
			title: ''
		},
		{
			img: 'texas.svg',
			link: '',
			title: ''
		},
		{
			img: 'nike.svg',
			link: '',
			title: ''
		},
		{
			img: 'starbucks.svg',
			link: '',
			title: ''
		}
	];
</script>

<section>
	<div class=" mx-auto bg-violet-600 px-5 py-24 lg:px-16">
		<div class="mb-8 flex w-full flex-col items-center text-center">
			<span
				class="mb-4 max-w-4xl text-center  text-2xl font-medium uppercase tracking-wide text-white"
			>
				Kto już stosuje podejścia produkcyjne Kanban i Lean manufacturing?
				<!-- <a
					href="https://www.wickedtemplates.com/expo.html"
					class="font-semibold text-blue-600 hover:text-blue-500 lg:mb-0">Our customers »</a
				> -->
			</span>
			<p class="mx-auto mt-8 max-w-xl text-base leading-relaxed text-white">
				Kanban może być zatem wykorzystywany w niemal każdym obszarze, w którym istnieje przepływ
				pracy, który można zwizualizować i usprawnić. Na przykład w takich dziedzinach jak:
				produkcja, obsługa klienta, opieka zdrowotna, edukacja, IT i rozwój oprogramowania,
				zarządzanie projektami.
			</p>
		</div>
		<div class="mx-auto text-center">
			<div class="mx-auto grid grid-cols-5 gap-x-4 gap-y-12 lg:grid-cols-5">
				{#each logos as logo}
					<div>
						<img class="mx-auto h-4 w-auto lg:h-20" src="./logos/{logo.img}" alt={logo.title} />
					</div>
				{/each}
			</div>
		</div>
	</div>
</section>
