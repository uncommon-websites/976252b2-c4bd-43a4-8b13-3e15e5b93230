<section class="bg-primary-100 py-24 px-6 md:px-12 relative overflow-hidden">
	<div class="max-w-7xl mx-auto grid grid-cols-1 lg:grid-cols-2 gap-12 items-center relative z-10">
		<div>
			<span class="font-mono text-[10px] text-gray-700 uppercase tracking-widest mb-4 block">
				[ ENTERPRISE INFRASTRUCTURE ]
			</span>
			<h2 class="font-display text-4xl md:text-5xl lg:text-6xl font-medium tracking-tight text-gray-900 mb-6 leading-[0.95]">
				Your Infrastructure<br>Knowledge Graph
			</h2>
			<p class="font-mono text-sm text-gray-800 max-w-md mb-8 leading-relaxed">
				AlphaCode maps your entire infrastructure ecosystem - from services and dependencies to deployment patterns and operational runbooks. Complete context enables reliable automation.
			</p>
			
			<button class="bg-black text-white px-5 py-2.5 rounded text-sm font-medium hover:bg-gray-800 transition-colors flex items-center gap-2 font-mono uppercase tracking-wide text-xs w-fit">
				Learn more ->
			</button>
		</div>

		<div class="relative h-[400px] w-full flex items-center justify-center">
			<!-- Infrastructure Graph Visualization -->
			<div class="absolute inset-0">
				<svg width="100%" height="100%" viewBox="0 0 400 300" class="overflow-visible">
					<!-- Nodes representing infrastructure components -->
                    <g fill="oklch(0.596 0.145 163.225)" stroke="#fff" stroke-width="1.5">
                        <!-- Central node (API Gateway) -->
                        <circle cx="200" cy="150" r="8" />
                        <!-- Service nodes -->
                        <circle cx="150" cy="100" r="6" />
                        <circle cx="250" cy="100" r="6" />
                        <circle cx="150" cy="200" r="6" />
                        <circle cx="250" cy="200" r="6" />
                        <!-- Database nodes -->
                        <circle cx="100" cy="150" r="5" />
                        <circle cx="300" cy="150" r="5" />
                        <!-- External services -->
                        <circle cx="180" cy="70" r="4" />
                        <circle cx="220" cy="70" r="4" />
                        <circle cx="180" cy="230" r="4" />
                        <circle cx="220" cy="230" r="4" />
                        <!-- Cache/Queue nodes -->
                        <circle cx="120" cy="80" r="4" />
                        <circle cx="280" cy="80" r="4" />
                    </g>
                    
                    <!-- Edges representing dependencies -->
                    <g stroke="oklch(0.696 0.17 162.48)" stroke-width="1" opacity="0.4">
                        <line x1="200" y1="150" x2="150" y2="100" />
                        <line x1="200" y1="150" x2="250" y2="100" />
                        <line x1="200" y1="150" x2="150" y2="200" />
                        <line x1="200" y1="150" x2="250" y2="200" />
                        <line x1="150" y1="100" x2="100" y2="150" />
                        <line x1="250" y1="100" x2="300" y2="150" />
                        <line x1="150" y1="200" x2="100" y2="150" />
                        <line x1="250" y1="200" x2="300" y2="150" />
                        <line x1="150" y1="100" x2="180" y2="70" />
                        <line x1="250" y1="100" x2="220" y2="70" />
                        <line x1="150" y1="200" x2="180" y2="230" />
                        <line x1="250" y1="200" x2="220" y2="230" />
                        <line x1="150" y1="100" x2="120" y2="80" />
                        <line x1="250" y1="100" x2="280" y2="80" />
                    </g>
                    
                    <!-- Labels -->
                    <g font-family="monospace" font-size="8" fill="#333" text-anchor="middle">
                        <text x="200" y="145">API</text>
                        <text x="100" y="145">DB</text>
                        <text x="300" y="145">Cache</text>
                    </g>
				</svg>
			</div>
		</div>
	</div>
    
    <!-- Background Grid Pattern -->
    <div class="absolute inset-0 z-0 opacity-10" 
        style="background-image: linear-gradient(#000 1px, transparent 1px), linear-gradient(90deg, #000 1px, transparent 1px); background-size: 40px 40px;">
    </div>
</section>
