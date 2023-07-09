<script>
	const browsers = [
		{
			title: 'Chrome',
			img: '/platforms/chrome.png',
			desc: 'latest',
			link: 'https://www.google.com/chrome/'
		},
		{
			title: 'Firefox',
			img: '/platforms/firefox.png',
			desc: 'latest',
			link: 'https://www.mozilla.org/en-US/firefox/new/?redirect_source=firefox-com'
		},
		{
			title: 'Edge',
			img: '/platforms/edge.png',
			desc: 'latest',
			link: 'https://www.microsoft.com/en-us/edge?form=MA13FJ&exp=e00'
		},
		{
			title: 'Safari',
			img: '/platforms/safari.png',
			desc: 'latest',
			link: 'https://www.apple.com/safari/'
		}
	];

	const technologies = [
		{
			title: 'Svelte',
			img: '/platforms/svelte.svg',

			desc: 'latest',
			link: 'https://kit.svelte.dev/'
		},
		{
			title: '.Net',
			img: '/platforms/.net.svg',

			desc: 'latest',
			link: 'https://dotnet.microsoft.com/en-us/'
		},
		{
			title: 'AWS',
			img: '/platforms/aws.svg',

			desc: 'Cloud',
			link: 'https://aws.amazon.com/'
		},
		{
			title: 'NFC',
			img: '/platforms/nfc.svg',

			desc: 'Near-field communication',
			link: 'https://nfc-forum.org/learn/nfc-technology/'
		}
	];
</script>

<section class="min-h-screen md:my-12 lg:my-12">
	<div
		class="relative mb-12 w-full max-w-5xl items-center rounded-xl py-12 md:mx-auto md:bg-gray-200 md:px-12 lg:mx-auto lg:bg-gray-200 lg:px-16"
	>
		<h2
			class="mb-8 text-center text-4xl font-bold leading-none tracking-tighter text-neutral-600  "
		>
			<!-- Our apps is supported in these modern browsers. -->
			Nasze aplikacje są obsługiwane w tych przeglądarkach.
		</h2>
		<div class="grid gap-6 lg:grid-cols-4 xl:gap-x-12">
			{#each browsers as technology}
				<div class=" mb-6 flex justify-center lg:mb-0">
					<div
						class="relative mb-4 block h-[100px] w-8/12 rounded-lg bg-neutral-700 shadow-[0_2px_15px_-3px_rgba(0,0,0,0.07),0_10px_20px_-2px_rgba(0,0,0,0.04)] lg:mb-0"
					>
						<div class="flex justify-center">
							<div
								class="relative mx-4 -mt-4  overflow-hidden rounded-lg bg-cover bg-no-repeat "
								data-te-ripple-init
								data-te-ripple-color="light"
							>
								<img src={technology.img} alt={technology.title} class="w-40 " />
								<a href="/">
									<div
										class="absolute top-0 right-0 bottom-0 left-0 h-full w-full overflow-hidden bg-[hsl(0,0%,98.4%,0.15)] bg-fixed opacity-0 transition duration-300 ease-in-out hover:opacity-100"
									/>
								</a>
							</div>
						</div>
						<!-- <div class="flex flex-col justify-center p-6">
							<h5 class="mb-4 text-center text-2xl font-bold">{technology.title}</h5>
							<p class="mb-6 text-center">
								{technology.desc}
							</p>

						</div> -->
					</div>
				</div>
			{/each}
		</div>
	</div>

	<div
		class="relative w-full max-w-5xl items-center rounded-xl py-12 md:mx-auto md:bg-gray-200 md:px-12 lg:mx-auto lg:bg-gray-200 lg:px-16"
	>
		<h2
			class="mb-8 text-center text-4xl font-bold leading-none tracking-tighter text-neutral-600  "
		>
			Nasza platforma jest zbudowana przy użyciu następujących technologii.
		</h2>
		<div class="grid gap-6 lg:grid-cols-4 xl:gap-x-12">
			{#each technologies as technology}
				<div class="mb-6 flex justify-center lg:mb-0">
					<div
						class="relative block h-[100px] rounded-lg bg-neutral-700 shadow-[0_2px_15px_-3px_rgba(0,0,0,0.07),0_10px_20px_-2px_rgba(0,0,0,0.04)]"
					>
						<div class="flex justify-center">
							<div
								class="relative mx-4 -mt-4  overflow-hidden rounded-lg bg-cover bg-no-repeat "
								data-te-ripple-init
								data-te-ripple-color="light"
							>
								<img src={technology.img} alt={technology.title} class="w-40 " />
								<a href="/">
									<div
										class="absolute top-0 right-0 bottom-0 left-0 h-full w-full overflow-hidden bg-[hsl(0,0%,98.4%,0.15)] bg-fixed opacity-0 transition duration-300 ease-in-out hover:opacity-100"
									/>
								</a>
							</div>
						</div>
						<!-- <div class="flex flex-col justify-center p-6">
							<h5 class="mb-4 text-center text-2xl font-bold">{technology.title}</h5>
							<p class="mb-6 text-center">
								{technology.desc}
							</p>

						</div> -->
					</div>
				</div>
			{/each}
		</div>
	</div>
</section>
