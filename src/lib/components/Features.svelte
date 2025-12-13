<script lang="ts">
	import FeatureCard from './FeatureCard.svelte';
</script>

<section class="py-24 px-6 md:px-12 max-w-7xl mx-auto relative" id="features">
    <!-- Background Grid Pattern -->
    <div class="absolute inset-0 z-0 opacity-30 pointer-events-none" 
        style="background-image: linear-gradient(#ccc 1px, transparent 1px), linear-gradient(90deg, #ccc 1px, transparent 1px); background-size: 40px 40px; mask-image: linear-gradient(to bottom, transparent, black 10%, black 90%, transparent);">
    </div>

	<div class="flex flex-col md:flex-row justify-between items-start md:items-end mb-16 gap-6 relative z-10">
		<div>
			<span class="font-mono text-[10px] text-gray-500 uppercase tracking-widest mb-4 block">
				[ AUTONOMOUS OPERATIONS ]
			</span>
			<h2 class="font-display text-4xl md:text-5xl lg:text-6xl font-medium tracking-tight text-gray-900 mb-4">
				DevOps that runs itself.
			</h2>
			<p class="font-mono text-sm text-gray-600 max-w-lg">
				AlphaCode captures your team's infrastructure knowledge and executes complex cloud operations autonomously.
			</p>
		</div>
		
		<button class="bg-black text-white px-5 py-2.5 rounded text-sm font-medium hover:bg-gray-800 transition-colors flex items-center gap-2 font-mono uppercase tracking-wide text-xs">
			See AlphaCode in action ->
		</button>
	</div>

	<div class="grid grid-cols-1 md:grid-cols-2 gap-6">
		<FeatureCard 
			subtitle="[ INTELLIGENT AUTOMATION ]"
			title="Execute complex<br>operations autonomously"
			description="AI agents that understand your infrastructure and execute deployments, scaling, and maintenance tasks."
			tagColor="bg-brand-green"
			tagIcon="arrow"
            imageSrc="/generated/image-devops-engineer-monitoring-multiple-dash-1765594998684-0.webp"
		/>
		
		<FeatureCard 
			subtitle="[ KNOWLEDGE CAPTURE ]"
			title="Transform tribal knowledge<br>into executable agents"
			description="Capture your team's DevOps expertise and make it accessible to autonomous agents at scale."
			tagColor="bg-accent-orange"
			tagIcon="plus"
            imageSrc="/generated/image-team-of-engineers-collaborating-around-a-1765595001256-1.webp"
		/>
		
		<FeatureCard 
			subtitle="[ CLOUD OPERATIONS ]"
			title="Multi-cloud infrastructure<br>management at scale"
			description="Deploy, monitor, and optimize across AWS, GCP, Azure, and Kubernetes with unified agents."
			tagColor="bg-accent-pink"
			tagIcon="arrow"
            imageSrc="/generated/image-wide-view-of-server-racks-and-data-cente-1765595003496-2.webp"
		/>
		
		<FeatureCard 
			subtitle="[ CONTINUOUS LEARNING ]"
			title="Agents that learn from<br>your team's patterns"
			description="AlphaCode learns from every operation, continuously improving automation quality and reliability."
			tagColor="bg-accent-yellow"
			tagIcon="plus"
            imageSrc="https://placehold.co/600x400/FFFFFF/E5E7EB?text=Learning+System"
		/>
	</div>
</section>
