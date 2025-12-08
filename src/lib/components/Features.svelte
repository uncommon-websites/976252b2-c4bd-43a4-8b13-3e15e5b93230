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
				[ SHIP FASTER ]
			</span>
			<h2 class="font-display text-4xl md:text-5xl lg:text-6xl font-medium tracking-tight text-gray-900 mb-4">
				Your second pair of eyes.
			</h2>
			<p class="font-mono text-sm text-gray-600 max-w-lg">
				Greptile automatically reviews PRs in Github and GitLab with full context of your codebase.
			</p>
		</div>
		
		<button class="bg-black text-white px-5 py-2.5 rounded text-sm font-medium hover:bg-gray-800 transition-colors flex items-center gap-2 font-mono uppercase tracking-wide text-xs">
			See Greptile in action ->
		</button>
	</div>

	<div class="grid grid-cols-1 md:grid-cols-2 gap-6">
		<FeatureCard 
			subtitle="[ IN-LINE COMMENTS ]"
			title="Get context-aware<br>comments on your PRs"
			description="In-line comments to identify bugs, antipatterns, security issues, and more."
			tagColor="bg-brand-green"
			tagIcon="arrow"
            imageSrc="https://placehold.co/600x400/FFFFFF/E5E7EB?text=PR+Comments+UI"
		/>
		
		<FeatureCard 
			subtitle="[ CUSTOM CONTEXT ]"
			title="Describe your coding<br>standards in English"
			description="Tell Greptile about your team's best practices. Greptile will enforce them across PRs."
			tagColor="bg-accent-orange"
			tagIcon="plus"
            imageSrc="https://placehold.co/600x400/FFFFFF/E5E7EB?text=Coding+Standards+UI"
		/>
		
		<FeatureCard 
			subtitle="[ PR SUMMARIES ]"
			title="Quickly understand PRs<br>with AI-generated summaries"
			description="Get mermaid diagrams, file-by-file breakdowns, and confidence scores for every PR."
			tagColor="bg-accent-pink"
			tagIcon="arrow"
            imageSrc="https://placehold.co/600x400/FFFFFF/E5E7EB?text=PR+Summaries+UI"
		/>
		
		<FeatureCard 
			subtitle="[ LEARNING ]"
			title="Greptile learns by<br>reading your comments"
			description="Greptile infers your team's coding standards by reading every engineer's comments on PRs."
			tagColor="bg-accent-yellow"
			tagIcon="plus"
            imageSrc="https://placehold.co/600x400/FFFFFF/E5E7EB?text=Learning+UI"
		/>
	</div>
</section>
