<script>
	import {
		Logos,
		RightPanel,
		LeftPanel,
		ShortDescription,
		Steps,
		Features,
		Team
	} from '../lib/widgets';

	const content = [
		{
			tag: '',
			title:
				'Производственная отчетность с подтверждением от независимой стороны в режиме реального времени',
			img: 'https://www.machinemetrics.com/hubfs/machinemetrics-production-performance-dashboard.png',
			desc: [
				'Предоставьте операторам и менеджерам информацию, необходимую для быстрого принятия решений.',
				' Простые приборные панели наглядно показывают, когда машины простаивают или отстают в производстве.'
			]
		},
		{
			tag: '',
			title: 'Исторические данные для глубокого анализа',
			img: 'https://www.machinemetrics.com/hubfs/manufacturing-production-report.png',
			desc: [
				'Исторические данные обеспечивают доступ к долгосрочным производственным данным, необходимым для глубокого анализа. ',
				'Разработайте более точное время цикла, детализируйте производительность отдельных машин и установите производственные контрольные показатели.'
			]
		},
		{
			tag: '',
			title: 'Визуализация и оптимизация производства',
			img: 'https://www.machinemetrics.com/hubfs/MM20_Tablet_opdash_tab_part-count.png',
			desc: [
				'установление точного времени цикла и уточнение стандартов работ для оптимизации планирования производства и максимального увеличения производственных мощностей.',
				''
			]
		},
		{
			tag: '',
			title: 'Прозрачность производственного процесса',
			img: 'https://www.machinemetrics.com/hubfs/mm20-laptop_0023_Reports-OEE_dropshadow.png',
			desc: [
				'Обеспечьте менеджерам и руководителям, и клиентам полную прозрачность над технологическим процессом, предоставляя им возможность в режиме реального времени видеть текущую производительность и инструменты для проведения углубленного бизнес-анализа.',
				''
			]
		},
		{
			tag: '',
			title: 'Оптимизация стандартов работы',
			img: 'https://www.machinemetrics.com/hubfs/mm20-laptop_0032_Machine_Settings_dropshadow.png',
			desc: [
				'Подробная отчетность и аналитика помогут вам усовершенствовать стандарты работы и выявить процессы, создающие "узкие места".'
			]
		}
		// {
		// 	tag: '',
		// 	title: '',
		// 	img: '',
		// 	desc: ['', '', '']
		// },
		// {
		// 	tag: '',
		// 	title: '',
		// 	img: '',
		// 	desc: ['', '', '']
		// }
	];
</script>

<!--  -->

<video
	class="video-hero"
	poster="https://www.machinemetrics.com/hubfs/machinemetrics-production-performance-dashboard.png"
	playsinline
	autoplay
	muted
	loop
>
	<!-- <source src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/4273/fashion.webm" type="video/webm" /> -->
	<source src="./video.mp4" type="video/mp4" />
</video>

<section class="min-h-screen">
	<div
		class="mix-blend-mode  mt-[18%]  flex w-full flex-col items-center justify-center text-center"
	>
		<h2
			class="max-w-5xl text-center text-4xl font-bold leading-none tracking-tighter text-neutral-50 md:text-5xl lg:max-w-7xl lg:text-6xl"
		>
			Witamy w <span class="font-black text-violet-500">Just in Time </span>
			<br class="hidden lg:block" /> production system
		</h2>
	</div>
</section>

<!-- <Hero /> -->

<ShortDescription />

<Logos />

<Features />

<Steps />

<h2 class="mt-12 text-center text-6xl  font-black text-violet-700">Загляните под капот</h2>

<RightPanel content={content[0]} />
<LeftPanel content={content[1]} />
<RightPanel content={content[2]} />
<LeftPanel content={content[3]} />
<RightPanel content={content[4]} />
<!-- <LeftPanel content={content[5]} /> -->

<Team />

<style>
	@media (max-width: 640px) {
		.justify-content-sm {
			justify-content: space-between;
		}
	}

	.justify-content {
		justify-content: space-between;
	}

	.mix-blend-mode {
		mix-blend-mode: screen;
	}
	.video-hero {
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
		object-fit: cover;
		object-position: center;
	}
	/* div#fashion {
		min-height: 100vh;
		display: flex;
		align-items: center;
		justify-content: center;
	} */
	header {
		position: fixed;
		width: 100%;
		text-align: center;
		color: white;
		transition: 0.4s;
	}
	header:hover {
		background: rgba(255, 255, 255, 0.8);
		color: #000;
	}
	/* h1 {
		font-family: Moderne Sans, sans-serif;
		text-align: center;
		font-size: 2rem;
		width: 100%;
		letter-spacing: 0.5rem;
	}
	nav a {
		text-decoration: none;
		color: inherit;
		padding: 1rem;
	} */
	/* h2 {
		font-size: 8vmin;
		text-align: center;
		margin: 2rem 4rem 0;
		mix-blend-mode: overlay;
		color: #fff;
		font-weight: 100;
	} */
</style>
