<script>
	const steps = [
		{
			title: 'Собирайте',
			desc: [
				'Автономный сбор, подключение и контекстуализация данных от машин и операторов в вашем цехе.'
			]
		},
		{
			title: 'Доступ',
			desc: [
				'Безопасный доступ к полным, пригодным для использования данным в режиме реального времени - в любом месте и в любое время - с помощью удобного для мобильных устройств облачного приложения'
			]
		},
		{
			title: 'Визуализируйте',
			desc: [
				'Мощные визуализации данных на производстве позволяют вашей команде оперативно и выполнять работы точно в срок.'
			]
		},
		{
			title: 'Анализируйте',
			desc: [
				'Проводите углубленный анализ данных в реальном времени и исторических данных с помощью надежных встроенных функций отчетности.'
			]
		},
		{
			title: 'Оптимизируйте',
			desc: [
				'Анализ производственных данных помогает определить стратегии повышения эффективности работы и измерить эффект от любых изменений процесса.'
			]
		},
		{
			title: 'Расширяйте возможности',
			desc: [
				'Цифровое преобразование операций, позволяющее операторам, менеджерам и руководителям получить информацию, основанную на данных.'
			]
		}
	];
</script>

<section>
	<h2 class=" text-center text-6xl  font-black text-violet-700">Как следить за производством</h2>
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
