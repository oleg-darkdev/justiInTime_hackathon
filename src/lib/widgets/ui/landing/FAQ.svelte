<script>
	const faq = [
		{
			title: 'Dlaczego System Produkcyjny Toyoty (TPS) został wybrany jako system produkcyjny?',
			desc: [
				'Kanban (system kanban) to odchudzona metoda zarządzania linią produkcyjną, która wykorzystuje karty informacyjne do przenoszenia zlecenia produkcyjnego z kolejnego procesu do poprzedniego.',
				'Narzędzie systemu ciągnięcia, które wskazuje na produkcję lub wycofanie (przeniesienie) elementów z jednego procesu do drugiego'
			]
		},
		{
			title: 'Jak wiarygodnym systemem produkcyjnym jest system Kanban?',
			desc: [
				'System Kanban został po raz pierwszy wprowadzony w latach 40. w Toyota Motor Corporation w Japonii. Był on częścią wysiłków firmy zmierzających do wdrożenia systemu lean manufacturing lub Toyota Production System (TPS). Kanban stał się ważnym narzędziem wspierającym zasadę produkcji just-in-time (JIT), która była kluczowym elementem TPS',
				'Z czasem zasady Kanban zaczęły być stosowane w różnych branżach i działaniach. W 2000 roku Kanban stał się szeroko stosowany w rozwoju oprogramowania i technologii informatycznych.'
			]
		},
		{
			title: 'Czy system Kanban jest odpowiedni dla istniejących przedsiębiorstw?',
			desc: [
				`Metoda Kanban jest odpowiednia dla istniejących przedsiębiorstw, które już doświadczają problemów w swoich łańcuchach: pomaga "poskładać" zadania i zbudować kompleksowy proces zorientowany na cel końcowy. Zrozumienie, ile zadań faktycznie znajduje się w procesie, gdzie i co blokuje ich realizację.`
			]
		},
		{
			title: 'W którym momencie można wdrożyć system produkcyjny kanban?',
			desc: [
				`System produkcyjny Kanban Metoda "Zacznij tam, gdzie jesteś teraz" obejmuje ewolucyjne wdrażanie zmian. Wieloetapowy proces jest niezwykle trudny do zmiany w rewolucyjny sposób. Miękkie zmiany są znacznie łatwiejsze do wdrożenia - i będą miały natychmiastowy efekt,`
			]
		},
		{
			title: 'Czym różnimy się od gotowych rozwiązań dostępnych na rynku?',
			desc: [
				`1. Budżetowe rozwiązanie fizyczne wraz z konsultacjami - przystępne cenowo dla małych firm.`,
				`2. Uniwersalne rozwiązanie i niezależnie od rodzaju działalności.`,
				`3. Możliwe jest przejście na droższe i bardziej złożone systemy wykorzystujące Kanban.`
			]
			// `4. `, `5. `, `6. `
		},
		{
			title: 'Jak wykorzystamy wysoką dokładność zapewnianą przez usługi e-Czas?',
			desc: [
				`Jeśli w zakładzie produkcyjnym znajduje się kilka sekcji lub urządzeń generujących dane w czasie rzeczywistym, nasz system ma możliwość nałożenia ich na wspólny wykres z dokładnością do milisekundy, bez konieczności gromadzenia dodatkowych danych.`,
				``
			]
		}
	];
</script>

<section class="bg-white py-6 sm:py-8 lg:py-12">
	<div class="mx-auto max-w-screen-xl px-4 md:px-8">
		<!-- text - start -->
		<div class="mb-8">
			<h2 class="mb-4 text-center text-2xl font-black text-violet-700  md:mb-6 lg:text-3xl">
				Odpowiedzi na możliwe pytania
			</h2>

			<p class="mx-auto max-w-screen-md text-center text-gray-500 md:text-lg">
				Zebraliśmy ważne informacje, które mogą pomóc.
			</p>
		</div>
		<a name="faq" />

		<div class="grid gap-4 sm:grid-cols-2 md:gap-8">
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
						<p class="mb-2 text-gray-100">
							{@html description}
						</p>
					{/each}
				</div>
			{/each}
			<!-- question - end -->
		</div>
	</div>
</section>
