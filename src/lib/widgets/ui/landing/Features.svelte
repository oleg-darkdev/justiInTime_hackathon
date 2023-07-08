<script>
	const features = [
		{
			icon: '',
			title:
				'Отчётность для клиентов о соблюдении технологического процесса с подтверждением независимых сервисов E-czas',
			description: ''
		},
		{
			icon: '',
			title:
				'Отслеживайте важнейшие производственные показатели с использованием метрик систем проиводств канбан  ',
			description: ''
		},

		{
			icon: '',
			title: 'Получайте мгновенные оповещения ',
			description: ''
		},
		{
			icon: '',
			title: 'Анализ и сокращение узких мест в производстве',
			description: ''
		},
		{
			icon: '',
			title: 'Снижение эксплуатационных расходов и простоев оборудования включенным',
			description: ''
		},
		{
			icon: '',
			title: '    Стандартизация рабочего места и процессов',
			description: ''
		},
		{
			icon: '',
			title:
				'Автоматические отчётность с подробным анализом согласно установленной технологической документации',
			description: ''
		}
	];
</script>

<section class="mx-auto py-12 md:px-6">
	<div class="flex flex-wrap">
		<div class="mb-6 w-full shrink-0 grow-0 basis-auto px-3 lg:mb-0 lg:w-4/12">
			<p class="text-primary-400 mb-6 font-bold uppercase ">Features</p>
			<h2 class="mb-6 text-3xl font-bold text-violet-600">
        Почему именно <span class='font-black text-4xl '>Just in Time</span>
			</h2>

			<p class="mb-12 text-neutral-300">
				Отчётность для клиентов о соблюдении технологического процесса с подтверждением независимых
				сервисов E-czas
			</p>
		</div>

		<div class="mb-md-0 mb-6 w-full shrink-0 grow-0 basis-auto px-3 lg:w-8/12">
			<div class="flex flex-wrap">
				{#each features as feature}
					<div class="mb-4 w-full shrink-0 grow-0 basis-auto lg:w-6/12 lg:px-3">
						<div class="flex">
							<div class="shrink-0">
								<!-- <div class="bg-primary-100 mb-6 inline-block rounded-md p-4 text-primary">
									<svg
										xmlns="http://www.w3.org/2000/svg"
										fill="none"
										viewBox="0 0 24 24"
										stroke-width="2"
										stroke="currentColor"
										class="h-6 w-6"
									>
										<path
											stroke-linecap="round"
											stroke-linejoin="round"
											d="M11.42 15.17L17.25 21A2.652 2.652 0 0021 17.25l-5.877-5.877M11.42 15.17l2.496-3.03c.317-.384.74-.626 1.208-.766M11.42 15.17l-4.655 5.653a2.548 2.548 0 11-3.586-3.586l6.837-5.63m5.108-.233c.55-.164 1.163-.188 1.743-.14a4.5 4.5 0 004.486-6.336l-3.276 3.277a3.004 3.004 0 01-2.25-2.25l3.276-3.276a4.5 4.5 0 00-6.336 4.486c.091 1.076-.071 2.264-.904 2.95l-.102.085m-1.745 1.437L5.909 7.5H4.5L2.25 3.75l1.5-1.5L7.5 4.5v1.409l4.26 4.26m-1.745 1.437l1.745-1.437m6.615 8.206L15.75 15.75M4.867 19.125h.008v.008h-.008v-.008z"
										/>
									</svg>
								</div> -->
							</div>
							<div class="ml-4 grow">
								<p class="mb-3 text-2xl font-bold text-gray-500">{feature.title}</p>
							</div>
						</div>
					</div>
				{/each}
			</div>
		</div>
	</div>
</section>
