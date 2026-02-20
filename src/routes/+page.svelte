<svelte:head>
	<title>BRUT. — Raw Design</title>
</svelte:head>

<!-- HERO SECTION — Asymmetric, intentionally broken layout -->
<section class="relative overflow-hidden border-b-4 border-black">
	<div class="grid grid-cols-1 lg:grid-cols-12 min-h-[80vh]">
		<!-- Left: massive heading that breaks out -->
		<div class="lg:col-span-7 flex flex-col justify-center px-8 py-16 lg:px-16 relative">
			<!-- Decorative offset block -->
			<div class="absolute top-8 right-0 w-32 h-32 bg-black opacity-10 -translate-y-4 translate-x-8 hidden lg:block"></div>

			<p class="text-sm font-bold uppercase tracking-[0.3em] mb-6 border-b-2 border-black pb-2 inline-block">
				Est. 2026 — No Curves, No Mercy
			</p>

			<h1 class="text-6xl sm:text-7xl md:text-8xl lg:text-[9rem] xl:text-[11rem] leading-none mb-8 -ml-1 lg:-mr-24 relative z-10" style="font-family: 'Space Grotesk', sans-serif;">
				RAW<br/>CONCRETE<br/>DESIGN
			</h1>

			<p class="text-lg max-w-xl mb-10 leading-relaxed">
				We strip away everything decorative. What remains is structure.
				Function. Weight. This is design that refuses to apologize.
			</p>

			<div class="flex flex-wrap gap-4 items-center">
				<a href="/" class="btn-brutal hover-brutal text-lg !py-5 !px-10">
					SIGN IN
				</a>
				<a href="/" class="font-bold text-sm uppercase tracking-widest border-b-2 border-black pb-1 no-underline hover:bg-black hover:text-white hover:px-3">
					VIEW WORK &rarr;
				</a>
			</div>
		</div>

		<!-- Right: stacked info blocks, asymmetric -->
		<div class="lg:col-span-5 bg-black text-white flex flex-col justify-between p-8 lg:p-12 border-l-4 border-black">
			<div>
				<h2 class="text-4xl lg:text-5xl mb-8 text-white" style="font-family: 'Space Grotesk', sans-serif;">
					NO RADIUS.<br/>NO GRADIENTS.<br/>NO APOLOGIES.
				</h2>
				<div class="w-24 h-1 bg-white mb-8"></div>
				<p class="text-lg leading-relaxed opacity-80">
					Every pixel has a purpose. Every element earns its space.
					Brutalism isn't a trend. It's an ethos.
				</p>
			</div>

			<div class="mt-12 grid grid-cols-2 gap-4">
				<div class="border-2 border-white p-4 hover-brutal">
					<p class="text-3xl font-black" style="font-family: 'Space Grotesk', sans-serif;">247</p>
					<p class="text-xs uppercase tracking-widest opacity-60 mt-1">Projects</p>
				</div>
				<div class="border-2 border-white p-4 hover-brutal">
					<p class="text-3xl font-black" style="font-family: 'Space Grotesk', sans-serif;">89K</p>
					<p class="text-xs uppercase tracking-widest opacity-60 mt-1">Lines Deleted</p>
				</div>
				<div class="border-2 border-white p-4 hover-brutal">
					<p class="text-3xl font-black" style="font-family: 'Space Grotesk', sans-serif;">0px</p>
					<p class="text-xs uppercase tracking-widest opacity-60 mt-1">Border Radius</p>
				</div>
				<div class="border-2 border-white p-4 hover-brutal">
					<p class="text-3xl font-black" style="font-family: 'Space Grotesk', sans-serif;">900</p>
					<p class="text-xs uppercase tracking-widest opacity-60 mt-1">Font Weight</p>
				</div>
			</div>
		</div>
	</div>
</section>

<!-- FEATURES — Broken grid with overlapping elements -->
<section class="px-8 lg:px-16 py-20 border-b-4 border-black">
	<div class="flex items-end justify-between mb-16">
		<h2 class="text-5xl lg:text-7xl" style="font-family: 'Space Grotesk', sans-serif;">
			PRINCIPLES
		</h2>
		<div class="hidden lg:block w-48 h-1 bg-black mb-3"></div>
	</div>

	<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-0">
		<div class="card-brutal hover-brutal p-8 md:p-10 border-b-0 md:border-b-3 md:border-r-0 lg:border-r-3">
			<span class="text-6xl font-black opacity-10 block mb-2" style="font-family: 'Space Grotesk', sans-serif;">01</span>
			<h3 class="text-2xl mb-4" style="font-family: 'Space Grotesk', sans-serif;">HONESTY</h3>
			<p class="leading-relaxed">
				Materials don't pretend to be something they're not.
				A div is a div. A border is a border. Nothing hides.
			</p>
		</div>
		<div class="card-brutal hover-brutal p-8 md:p-10 border-b-0 md:border-b-3 md:border-r-0 lg:border-r-3 md:-mt-4 lg:mt-0 lg:-mt-6">
			<span class="text-6xl font-black opacity-10 block mb-2" style="font-family: 'Space Grotesk', sans-serif;">02</span>
			<h3 class="text-2xl mb-4" style="font-family: 'Space Grotesk', sans-serif;">WEIGHT</h3>
			<p class="leading-relaxed">
				Every element carries visual mass. Nothing floats.
				Nothing fades. Everything lands with impact.
			</p>
		</div>
		<div class="card-brutal hover-brutal p-8 md:p-10 md:col-span-2 lg:col-span-1 md:mt-0 lg:-mt-12">
			<span class="text-6xl font-black opacity-10 block mb-2" style="font-family: 'Space Grotesk', sans-serif;">03</span>
			<h3 class="text-2xl mb-4" style="font-family: 'Space Grotesk', sans-serif;">STRUCTURE</h3>
			<p class="leading-relaxed">
				The grid is visible. The bones show through.
				Decoration is stripped. Function remains.
			</p>
		</div>
	</div>
</section>

<!-- CTA BAND -->
<section class="bg-black text-white px-8 lg:px-16 py-16 flex flex-col lg:flex-row items-center justify-between gap-8">
	<h2 class="text-4xl lg:text-6xl text-white" style="font-family: 'Space Grotesk', sans-serif;">
		READY TO BUILD<br class="hidden lg:block" /> WITHOUT MERCY?
	</h2>
	<a href="/" class="btn-brutal !bg-white !text-black !border-white hover:!bg-black hover:!text-white hover:!border-white shrink-0 text-lg !py-5 !px-10">
		GET STARTED
	</a>
</section>

<!-- FOOTER -->
<footer class="px-8 lg:px-16 py-8 border-t-4 border-black flex flex-col sm:flex-row items-center justify-between gap-4">
	<p class="text-sm font-bold uppercase tracking-widest">&copy; 2026 BRUT. ALL RIGHTS RESERVED.</p>
	<p class="text-xs uppercase tracking-widest opacity-50">NO CURVES WERE HARMED IN THE MAKING OF THIS SITE</p>
</footer>
