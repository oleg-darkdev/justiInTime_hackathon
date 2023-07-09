<script>
	const faq = [
		{
			title: 'Почему система производства на основе Канбан',
			desc: [
				`Канбан (kanban, система канбан) — это метод управления бережливыми производственными линиями (японское слово, обозначающее «сигнал» или «карточка»), использующий информационные карточки для передачи заказа на изготовление с последующего процесса на предыдущий.`,
				`Инструмент вытягивающей системы, который дает указание на производство или изъятие (передачу) изделий с одного процесса на другой.`
			]
		},
		{
			title: 'На сколько Канбан надёжен в качестве системы производства',
			desc: [
				`истема Kanban впервые была внедрена в 1940-е годы в компании Toyota Motor Corporation в Японии. Это было частью усилий компании по внедрению системы "бережливого производства" или Toyota Production System (TPS). Kanban стал важным инструментом для поддержания принципа "just-in-time" (JIT) производства, который был ключевым элементом TPS.`,
				`С течением времени принципы Kanban стали применяться в различных отраслях и областях деятельности. В 2000-е годы система Kanban стала широко использоваться в области разработки программного обеспечения и информационных технологий. Это было частично благодаря работе таких людей, как Дэвид Андерсон, который адаптировал принципы Kanban для управления работой в области IT.`
			]
		},
		{
			title: 'Канбан для уже действующих предприятий',
			desc: [
				`Канбан-метод походіт для уже действуюшіх предпріятій іспытыювашіх проьлемы в своіх цепочках: помогает «собрать» задачу воедино и выстроить сквозной процесс, ориентированный на достижение конечной цели. Понять, сколько задач фактически находится внутри процесса, где и что блокирует их выполнение.`,
				``
			]
		},
		{
			title: 'В какой момент можно внедрят канбан систему производства',
			desc: [
				`Канбан сістема проізводства также Метод «начните с того, что вы делаете сейчас» предполагает эволюционное внедрение изменений. Многоэтапный процесс крайне сложно изменить революционно. Мягкие изменения внедрить гораздо проще — и они сразу дадут результат.`,
				``
			]
		},
		{
			title: 'В чём наше главное отличие от готовых решений на рынке',
			desc: [``, ``]
		},
		{
			title: '',
			desc: [``, ``]
		},
		{
			title: '',
			desc: [``, ``]
		}
	];
</script>

<section class="min-h-screen  bg-white py-6 sm:py-8 lg:py-12">
	<div class="mx-auto max-w-screen-xl px-4 md:px-8">
		<!-- text - start -->
		<div class="mb-8">
			<h2 class="mb-4 text-center text-2xl font-bold text-gray-800 md:mb-6 lg:text-3xl">
				Frequently asked questions
			</h2>

			<p class="mx-auto max-w-screen-md text-center text-gray-500 md:text-lg">
				This is a section of some simple filler text, also known as placeholder text. It shares some
				characteristics of a real written text but is random or otherwise generated.
			</p>
		</div>
		<!-- text - end -->
		<a name="faq" />

		<div class="grid gap-4 sm:grid-cols-2 md:gap-8">
			<!-- question - start -->
			{#each faq as data}
				<div class="rounded-lg bg-violet-500 p-5">
					<div class="mb-4 flex items-center justify-between gap-4 border-b pb-4">
						<h3 class="font-semibold text-white sm:text-lg md:text-xl">
							{data.title}
						</h3>

						<span
							class="inline-flex h-8 w-8 shrink-0 items-center justify-center rounded-full bg-gray-300 text-gray-500"
						>
							<svg
								xmlns="http://www.w3.org/2000/svg"
								class="h-6 w-6"
								viewBox="0 0 20 20"
								fill="currentColor"
							>
								<path
									fill-rule="evenodd"
									d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-8-3a1 1 0 00-.867.5 1 1 0 11-1.731-1A3 3 0 0113 8a3.001 3.001 0 01-2 2.83V11a1 1 0 11-2 0v-1a1 1 0 011-1 1 1 0 100-2zm0 8a1 1 0 100-2 1 1 0 000 2z"
									clip-rule="evenodd"
								/>
							</svg>
						</span>
					</div>
					{#each data.desc as description}
						<p class="text-gray-100">
							{@html description}
						</p>
					{/each}
				</div>
			{/each}
			<!-- question - end -->
		</div>
	</div>
</section>
