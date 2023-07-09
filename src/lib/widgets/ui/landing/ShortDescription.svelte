<script>
	const content = [
		{
			title: 'Системы производства проверенные временнем.',
			icon: '',
			desc: [
				'Системы производства, необходимые вам для принятия более быстрых, умных и уверенных решений, уже есть. Вам нужно только начать использовать их.',
				'Justi in time - это простое IoT решение на основе Kanban Production, которое дает вашей команде мгновенный доступ к глубоким производственным данным.'
			]
		},
		{
			title:
				'Почему отслеживание производства является обязательным условием современного производства',
			icon: '',
			desc: [
				'Инновации в производственных технологиях находятся на пике, но бывает трудно понять, с чего начать. Вам нужно решение, которое легко внедрить, просто использовать и которое дает преобразующую информацию. Именно таким решением является отслеживание производства в режиме реального времени с помощью MachineMetrics. Основные преимущества включают:',
				''
			]
		},
		{
			title: 'Обучение перед началом использования.',
			icon: '',
			desc: [
				'В интернете очень много информации Toyota Production System, мы предлагаем вам ознакомиться с системой через симуляционную настольную игру.',
				''
			]
		}
		// {
		// 	title: '',
		// 	icon: '',
		// 	desc: ['', '']
		// },
		// {
		// 	title: '',
		// 	icon: '',
		// 	desc: ['', '']
		// }
	];
</script>

<section class="-mt-60">
	<div
		class="relative  mx-auto w-full max-w-7xl items-center px-5 py-12 md:px-12 lg:px-16 lg:py-24"
	>
		<div class="mx-auto flex w-full text-left">
			<div class="relative mx-auto inline-flex items-center align-middle">
				<div class="text-center">
					<h1
						class="max-w-5xl text-2xl font-bold leading-none tracking-tighter text-violet-700 md:text-5xl lg:max-w-7xl lg:text-5xl"
					>
						Utwórz przejrzysty system Kanban
						<br class="hidden lg:block" />
						dla swojego małego <br class="hidden lg:block" /> zakładu produkcyjnego.
					</h1>
					<p class="mx-auto mt-8 max-w-xl text-base leading-relaxed text-gray-500">
						<span class='text-violet-500 font-black text-2xl'>Just in time </span> to budżetowe rozwiązanie, które umożliwia w czasie rzeczywistym
						synchronizację systemów Kanban produkcji offline i online.
					</p>
					<p class="mx-auto mt-8 max-w-xl text-base leading-relaxed text-gray-500">
						Nasze rozwiązanie koncentruje się na kontroli i raportowaniu czasu procesu zgodnie z
						dokumentacją w małych firmach.
					</p>
					<div class="mx-auto mt-6 flex w-full max-w-2xl justify-center items-center gap-2">
						<div class="mt-3 rounded-lg sm:mt-0">
							<a
								href="#more"
								class="transform rounded-xl bg-violet-600 px-5 py-4 text-center text-base font-medium text-white transition duration-500 ease-in-out hover:bg-violet-700 focus:outline-none focus:ring-2 focus:ring-violet-500 focus:ring-offset-2 lg:px-10"
								>Więcej informacji</a
							>
						</div>
						<div class="mt-3 rounded-lg sm:mt-0 sm:ml-3">
							<a
								href="#more"
								class="block transform items-center rounded-xl border-2 border-white px-5 py-3.5 text-center text-base font-medium text-blue-600 shadow-md transition duration-500 ease-in-out focus:outline-none focus:ring-2 focus:ring-gray-500 focus:ring-offset-2 lg:px-10"
								>Interfejs demo</a
							>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>

	<div class=" mx-auto flex max-w-7xl flex-col items-center px-5  sm:px-6 lg:px-8">
		<!-- <div class="prose-violet prose mx-auto flex w-full max-w-3xl flex-col text-left">
			<div class="mx-auto w-full">
				<h1 class="text-violet-700">A small headline to switch your visitors into users.</h1>
				<h2 class="text-violet-500">A small headline to switch your visitors into users.</h2>
				<p>
					Right. Say that again. No, no, George, look, it's just an act, right? Okay, so 9:00 you're
					strolling through the parking lot, you see us struggling.
				</p>
			</div>
		</div> -->
		{#each content as block}
			<div
				class="mx-auto my-10 flex max-w-7xl flex-col items-center border-b border-gray-200 pb-10 sm:flex-row"
			>
				<!-- <div
				class="inline-flex h-20 w-20 flex-shrink-0 items-center justify-center rounded-full bg-gray-50 text-neutral-600 sm:mr-10"
			>
				<svg
					fill="none"
					stroke="currentColor"
					stroke-linecap="round"
					stroke-linejoin="round"
					stroke-width="1.5"
					class="h-10 w-10"
					viewBox="0 0 24 24"
				>
					<path stroke="none" d="M0 0h24v24H0z" fill="none" />
					<circle cx="12" cy="12" r="9" />
					<line x1="3.6" y1="15" x2="14.15" y2="15" />
					<line x1="3.6" y1="15" x2="14.15" y2="15" transform="rotate(72 12 12)" />
					<line x1="3.6" y1="15" x2="14.15" y2="15" transform="rotate(144 12 12)" />
					<line x1="3.6" y1="15" x2="14.15" y2="15" transform="rotate(216 12 12)" />
					<line x1="3.6" y1="15" x2="14.15" y2="15" transform="rotate(288 12 12)" />
				</svg>
			</div> -->
				<div class="prose-md prose mt-6 flex-grow text-center sm:mt-0 sm:text-left">
					<h2 class="text-center text-violet-500">{block.title}</h2>
					{#each block.desc as desc}
						<p class="text-center text-gray-500">
							{desc}
						</p>
					{/each}
				</div>
			</div>
		{/each}
	</div>
</section>
