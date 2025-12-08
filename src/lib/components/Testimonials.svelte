<script lang="ts">
	const testimonials = [
		{
			quote: "We've tried more code review tools than I can count. Greptile outperforms them all by a mile. Honestly the only AI reviewer that doesn't annoy the shit out of me.",
			author: "James",
			role: "CTO • Brex",
			image: "https://i.pravatar.cc/150?u=james",
            icon: "https://placehold.co/20x20/333/fff?text=B"
		},
		{
			quote: "We've been impressed by Greptile's code review quality. It's tightened our feedback loops, improved consistency, and freed up engineers to focus on higher-level design and architecture.",
			author: "Mark",
			role: "Eng Manager • Vercel",
			image: "https://i.pravatar.cc/150?u=mark",
            icon: "https://placehold.co/20x20/000/fff?text=V"
		},
		{
			quote: "Greptile helps the team do their best work. It levels everybody up and helps ensure that we're all proud of our code",
			author: "Anirudh",
			role: "Tech Lead • Sourcegraph",
			image: "https://i.pravatar.cc/150?u=anirudh",
            icon: "https://placehold.co/20x20/purple/fff?text=S"
		},
		{
			quote: "Greptile is one of the most impressive AI code review tools I've used. It's right up there with Cursor in terms of changing the game.",
			author: "Marlin",
			role: "CTO • Ponder.sh",
			image: "https://i.pravatar.cc/150?u=marlin",
            icon: "https://placehold.co/20x20/blue/fff?text=P"
		},
		{
			quote: "I'm thankful for the things Greptile catches in my pull requests.",
			author: "Hahnbee",
			role: "CTO • Mintlify",
			image: "https://i.pravatar.cc/150?u=hahnbee",
            icon: "https://placehold.co/20x20/green/fff?text=M"
		},
		{
			quote: "Greptile has been the first AI code review tool I've used that actually provides useful feedback on PRs. It's catching issues that human reviewers easily miss and giving senior-level suggestions to boot",
			author: "Chase",
			role: "CTO • Million.js",
			image: "https://i.pravatar.cc/150?u=chase",
            icon: "https://placehold.co/20x20/red/fff?text=M"
		},
        {
			quote: "Took me a year, but I finally signed up -- wow. Greptile's code reviews are very good. Been using this for a few weeks now, the team is very responsive! Highly recommended!",
			author: "Chris",
			role: "CTO • Sentry",
			image: "https://i.pravatar.cc/150?u=chris",
            icon: "https://placehold.co/20x20/333/fff?text=S"
		},
        {
			quote: "Took just 15 min to do the setup and it's been a game-changer. It catches small bugs that could easily slip through in big PRs and speeds up our release cycle.",
			author: "Harish",
			role: "CTO • Flexpa",
			image: "https://i.pravatar.cc/150?u=harish",
            icon: "https://placehold.co/20x20/orange/fff?text=F"
		}
	];
</script>

<section class="py-24 px-6 md:px-12 max-w-7xl mx-auto">
	<div class="text-center mb-16">
		<span class="font-mono text-[10px] text-gray-500 uppercase tracking-widest mb-4 block">
			[ TESTIMONIALS ]
		</span>
		<h2 class="font-display text-4xl md:text-5xl font-medium tracking-tight text-gray-900 mb-4">
			From Developers That Use Greptile
		</h2>
		<p class="font-mono text-sm text-gray-600">
			See what developers are saying about their experience with Greptile
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
