<script lang="ts">
	// Logos
	const logos = [
		{ name: 'HashiCorp', width: 90 },
		{ name: 'Datadog', width: 80 },
		{ name: 'PagerDuty', width: 90 },
		{ name: 'Atlassian', width: 80 },
		{ name: 'GitLab', width: 70 },
		{ name: 'CircleCI', width: 80 },
		{ name: 'Snyk', width: 60 },
		{ name: 'LaunchDarkly', width: 100 },
		{ name: 'Cockroach Labs', width: 100 },
		{ name: 'Temporal', width: 80 }
	];
</script>

<section class="relative pt-32 pb-16 px-6 md:px-12 max-w-7xl mx-auto min-h-screen flex flex-col justify-between">
	<div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
		<div class="z-10">
			<h1 class="text-6xl md:text-7xl lg:text-8xl font-display font-medium text-gray-900 leading-[0.9] tracking-tight mb-8">
				Autonomous DevOps at Scale
			</h1>
			
			<div class="relative w-12 h-12 mb-8">
				<!-- Cloud/Infrastructure icon -->
				<svg viewBox="0 0 24 24" fill="none" class="w-10 h-10 text-primary-400 absolute top-0 left-0">
					<path d="M18 10h-1.26A8 8 0 1 0 9 20h9a5 5 0 0 0 0-10z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="none"/>
				</svg>
			</div>

			<div class="space-y-6 max-w-lg">
				<p class="font-mono text-sm text-gray-700 uppercase tracking-wider leading-relaxed">
					Transform your DevOps knowledge<br>
					into autonomous AI agents that<br>
					execute complex cloud operations
				</p>

				<div class="flex flex-col items-start gap-3">
					<button class="bg-black text-white px-6 py-3 rounded text-sm font-medium hover:bg-gray-800 transition-colors flex items-center gap-2">
						Request Demo
						<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
					</button>
					<p class="text-[10px] text-gray-500 font-mono uppercase tracking-wide">
						Trusted by scaling startups • Enterprise-ready
					</p>
				</div>
			</div>
		</div>

		<div class="relative h-[400px] lg:h-[600px] w-full flex items-center justify-center">
			<!-- DevOps Workspace Image -->
			<div class="absolute inset-0 flex items-center justify-center rounded-lg overflow-hidden">
				<img src="/generated/image-devops-engineer-working-at-a-modern-desk-1765594481208-0.webp" alt="DevOps Engineer at Work" class="w-full h-full object-cover rounded-lg shadow-2xl" />
			</div>
		</div>
	</div>

	<div class="mt-20 border-t border-gray-300 pt-8">
		<div class="flex items-center gap-2 text-[10px] font-mono uppercase tracking-wider text-gray-600 mb-6">
			Trusted by DevOps teams at scaling startups
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
