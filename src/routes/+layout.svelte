<script lang="ts">
	import '../app.css';

	let { children } = $props();
</script>

<!-- Thick black sidebar with rotated vertical text -->
<div class="flex min-h-screen">
	<!-- LEFT SIDEBAR -->
	<aside class="hidden md:flex w-16 bg-black flex-col items-center justify-center border-r-4 border-black shrink-0">
		<span class="text-vertical text-white font-black text-sm tracking-[0.3em] uppercase select-none" style="font-family: 'Space Grotesk', sans-serif;">
			BRUTALISM / 2026
		</span>
	</aside>

	<!-- MAIN CONTENT -->
	<div class="flex-1 flex flex-col min-w-0">
		<!-- BRUTALIST APPBAR -->
		<nav class="flex items-center justify-between px-6 py-4 bg-[#E8E4DE] border-b-4 border-black">
			<div class="flex items-center gap-4">
				<!-- Logo block -->
				<div class="w-10 h-10 bg-black"></div>
				<span class="font-black text-xl uppercase tracking-tight" style="font-family: 'Space Grotesk', sans-serif;">
					BRUT.
				</span>
			</div>

			<div class="hidden sm:flex items-center gap-6">
				<a href="/" class="font-bold text-sm uppercase tracking-widest no-underline hover:bg-black hover:text-white px-2 py-1 border-2 border-transparent hover:border-black">
					HOME
				</a>
				<a href="/" class="font-bold text-sm uppercase tracking-widest no-underline hover:bg-black hover:text-white px-2 py-1 border-2 border-transparent hover:border-black">
					WORK
				</a>
				<a href="/" class="font-bold text-sm uppercase tracking-widest no-underline hover:bg-black hover:text-white px-2 py-1 border-2 border-transparent hover:border-black">
					ABOUT
				</a>
			</div>

			<button class="btn-brutal text-sm !py-3 !px-6">
				SIGN IN
			</button>
		</nav>

		<!-- PAGE CONTENT -->
		<main class="flex-1">
			{@render children()}
		</main>
	</div>
</div>
