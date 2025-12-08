<script lang="ts">
	// Logos
	const logos = [
		{ name: 'Brex', width: 80 },
		{ name: 'Substack', width: 90 },
		{ name: 'Bilt', width: 60 },
		{ name: 'Klaviyo', width: 80 },
		{ name: 'PostHog', width: 90 },
		{ name: 'Raycast', width: 80 },
		{ name: 'Browserbase', width: 100 },
		{ name: 'Mintlify', width: 80 },
		{ name: 'Crossmint', width: 90 },
		{ name: 'Pylon', width: 60 }
	];
</script>

<section class="relative pt-32 pb-16 px-6 md:px-12 max-w-7xl mx-auto min-h-screen flex flex-col justify-between">
	<div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
		<div class="z-10">
			<h1 class="text-6xl md:text-7xl lg:text-8xl font-display font-medium text-brand-green leading-[0.9] tracking-tight mb-8">
				The AI Code Reviewer
			</h1>
			
			<div class="relative w-12 h-12 mb-8">
				<!-- Fly icon/illustration -->
				<svg viewBox="0 0 24 24" fill="none" class="w-8 h-8 text-gray-400 absolute top-0 left-0 animate-bounce">
					<path d="M12 2L15 8L21 9L17 14L18 20L12 17L6 20L7 14L3 9L9 8L12 2Z" fill="currentColor" opacity="0.5"/>
				</svg>
			</div>

			<div class="space-y-6 max-w-lg">
				<p class="font-mono text-sm text-brand-green uppercase tracking-wider leading-relaxed">
					AI AGENTS THAT CATCH BUGS<br>
					IN YOUR PULL REQUESTS WITH<br>
					FULL CONTEXT OF YOUR CODEBASE
				</p>

				<div class="flex flex-col items-start gap-3">
					<button class="bg-brand-green text-white px-6 py-3 rounded text-sm font-medium hover:bg-brand-green-hover transition-colors flex items-center gap-2">
						Try For Free 
						<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
					</button>
					<p class="text-[10px] text-gray-500 font-mono uppercase tracking-wide">
						no credit card required - 14-day free trial
					</p>
				</div>
			</div>
		</div>

		<div class="relative h-[400px] lg:h-[600px] w-full flex items-center justify-center">
			<!-- Lizard Illustration Placeholder -->
			<div class="absolute inset-0 flex items-center justify-center opacity-80 mix-blend-multiply">
				<!-- This is a complex engraving style illustration. Using a placeholder SVG representation. -->
				<svg viewBox="0 0 400 400" class="w-full h-full text-gray-400" fill="currentColor">
					<path d="M100,300 Q150,250 200,300 T300,300" stroke="currentColor" stroke-width="2" fill="none" />
					<circle cx="200" cy="200" r="150" fill="currentColor" opacity="0.1" />
					<text x="50%" y="50%" text-anchor="middle" font-family="serif" font-size="24" fill="#666">Engraving of Lizard</text>
				</svg>
                <!-- In a real implementation, this would be an <img> tag with the specific asset -->
                <img src="https://placehold.co/600x600/EAEAE8/666666?text=Lizard+Engraving" alt="Lizard" class="w-full h-full object-contain mix-blend-multiply grayscale contrast-125" />
			</div>
		</div>
	</div>

	<div class="mt-20 border-t border-gray-300 pt-8">
		<div class="flex items-center gap-2 text-[10px] font-mono uppercase tracking-wider text-gray-600 mb-6">
			1000+ SOFTWARE TEAMS USE GREPTILE TO SHIP FASTER. 
			<a href="/" class="text-brand-green hover:underline flex items-center gap-1">
				SEE WHY TEAMS <span class="text-xs">♥</span> GREPTILE ->
			</a>
		</div>
		
		<div class="grid grid-cols-2 md:grid-cols-5 gap-8 opacity-60 grayscale">
			{#each logos as logo}
				<div class="h-8 flex items-center justify-center border border-gray-300/50 rounded bg-gray-100/50">
					<span class="text-xs font-bold text-gray-500">{logo.name}</span>
				</div>
			{/each}
		</div>
	</div>
</section>
