<script>
  export let content;
</script>


<section>
	<div class="mx-auto max-w-7xl px-4 py-6 sm:px-6 md:px-12 lg:px-24 ">
		<div class="mx-auto flex max-w-7xl flex-wrap items-center">
			<div class="w-full rounded-xl lg:w-1/2 lg:max-w-lg">
				<div>
					<div class="relative w-full max-w-lg">
						<div
							class="animate-blob absolute top-0 -left-4 h-72 w-72 rounded-full bg-violet-300 opacity-70 mix-blend-multiply blur-xl filter"
						/>

						<div
							class="animate-blob animation-delay-4000 absolute -bottom-24 right-20 h-72 w-72 rounded-full bg-fuchsia-300 opacity-70 mix-blend-multiply blur-xl filter"
						/>
						<div class="relative">
							<img
								class="mx-auto rounded-lg object-cover object-center shadow-2xl"
								alt="hero"
								src="{content.img}"
							/>
						</div>
					</div>
				</div>
			</div>
			<div
				class="mt-12 mb-16 flex flex-col items-start text-left md:mb-0 lg:w-1/2 lg:flex-grow lg:pl-6 xl:mt-0 xl:pl-24"
			>
				<span class="mb-8 text-xs font-bold uppercase tracking-widest text-violet-500">
					{content.tag}
				</span>
				<h1
					class="mb-8 text-4xl font-bold leading-none tracking-tighter text-violet-600 md:text-7xl lg:text-5xl"
				>
					{content.title}
				</h1>
        {#each content.desc as desc}
				<p class="mb-8 text-left text-base leading-relaxed text-gray-500">
					{desc}
				</p>
        {/each}

			</div>
		</div>
	</div>
</section>
