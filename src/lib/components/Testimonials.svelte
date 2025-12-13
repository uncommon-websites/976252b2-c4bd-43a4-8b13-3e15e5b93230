<script lang="ts">
	const testimonials = [
		{
			quote: "AlphaCode transformed how we handle infrastructure. We went from 3 DevOps engineers struggling to keep up, to autonomous agents handling 80% of our operations. Game-changing.",
			author: "Sarah Chen",
			role: "VP Engineering • TechFlow",
			image: "https://i.pravatar.cc/150?u=sarah",
            icon: "https://placehold.co/20x20/333/fff?text=T"
		},
		{
			quote: "The tribal knowledge capture is incredible. Years of DevOps expertise that lived in people's heads is now executable by AI agents. We're deploying 10x more frequently with the same team size.",
			author: "Marcus Rodriguez",
			role: "CTO • DataScale",
			image: "https://i.pravatar.cc/150?u=marcus",
            icon: "https://placehold.co/20x20/000/fff?text=D"
		},
		{
			quote: "AlphaCode handles our entire Kubernetes scaling strategy autonomously. It learned our traffic patterns and now scales services before we even see the load spike.",
			author: "Priya Sharma",
			role: "DevOps Lead • CloudNative",
			image: "https://i.pravatar.cc/150?u=priya",
            icon: "https://placehold.co/20x20/purple/fff?text=C"
		},
		{
			quote: "We were drowning in infrastructure complexity. AlphaCode gave us back our weekends. The agents handle deployments, rollbacks, and incident response better than we ever could manually.",
			author: "James Wilson",
			role: "Infrastructure Lead • Velocity",
			image: "https://i.pravatar.cc/150?u=james-w",
            icon: "https://placehold.co/20x20/blue/fff?text=V"
		},
		{
			quote: "The learning capability is mind-blowing. Every deployment teaches the agents something new. Our infrastructure operations get more reliable every week.",
			author: "Lisa Park",
			role: "SRE Manager • ScaleOps",
			image: "https://i.pravatar.cc/150?u=lisa",
            icon: "https://placehold.co/20x20/green/fff?text=S"
		},
		{
			quote: "AlphaCode reduced our mean time to recovery from 45 minutes to under 5. The agents detect issues and execute remediation playbooks faster than any human team could.",
			author: "David Kim",
			role: "CTO • ReliableStack",
			image: "https://i.pravatar.cc/150?u=david-k",
            icon: "https://placehold.co/20x20/red/fff?text=R"
		},
        {
			quote: "We onboard new engineers in days instead of months. AlphaCode captures all our operational knowledge and makes it accessible to everyone on the team.",
			author: "Emily Torres",
			role: "Engineering Manager • BuildFast",
			image: "https://i.pravatar.cc/150?u=emily",
            icon: "https://placehold.co/20x20/333/fff?text=B"
		},
        {
			quote: "Setup took 30 minutes. Within a week, AlphaCode was handling our entire deployment pipeline. The ROI is insane - we're shipping features 3x faster.",
			author: "Alex Johnson",
			role: "Head of Platform • ShipIt",
			image: "https://i.pravatar.cc/150?u=alex-j",
            icon: "https://placehold.co/20x20/orange/fff?text=S"
		}
	];
</script>

<section class="py-24 px-6 md:px-12 max-w-7xl mx-auto">
	<div class="text-center mb-16">
		<span class="font-mono text-[10px] text-gray-500 uppercase tracking-widest mb-4 block">
			[ TESTIMONIALS ]
		</span>
		<h2 class="font-display text-4xl md:text-5xl font-medium tracking-tight text-gray-900 mb-4">
			From DevOps Teams Using AlphaCode
		</h2>
		<p class="font-mono text-sm text-gray-600">
			See how engineering teams are scaling their infrastructure with autonomous agents
		</p>
	</div>

	<div class="columns-1 md:columns-2 lg:columns-3 gap-6 space-y-6">
		{#each testimonials as t}
			<div class="bg-white p-6 rounded-lg border border-gray-200 shadow-sm break-inside-avoid hover:shadow-md transition-shadow">
				<p class="font-mono text-xs leading-relaxed text-gray-700 mb-6">
					"{t.quote}"
				</p>
				<div class="flex items-center justify-between border-t border-gray-100 pt-4">
					<div class="flex items-center gap-3">
						<img src={t.image} alt={t.author} class="w-8 h-8 rounded-full bg-gray-200" />
						<div>
							<div class="text-xs font-bold text-gray-900">{t.author}</div>
							<div class="text-[10px] text-gray-500 font-mono">{t.role}</div>
						</div>
					</div>
                    <img src={t.icon} alt="Company Logo" class="w-5 h-5 rounded-sm opacity-70 grayscale" />
				</div>
			</div>
		{/each}
	</div>
</section>
