<script lang="ts">
	import { onMount } from 'svelte';
</script>

<section class="relative pt-32 pb-20 overflow-hidden bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="max-w-4xl">
			<h1 class="text-6xl md:text-7xl lg:text-[5.5rem] leading-[1.1] font-normal tracking-tight mb-8">
				Voice-activated guidance<br />
				for <span class="italic font-light">hospitality operators</span>
			</h1>

			<p class="text-xl text-gray-400 max-w-2xl mb-10 leading-relaxed font-light font-sans">
				Transform static procedures into real-time, hands-free knowledge access. 
				Empower your operators with contextual guidance exactly when they need it.
			</p>

			<div class="flex flex-wrap gap-4 mb-20">
				<a href="#demo" class="bg-primary-500 hover:bg-primary-600 text-white px-8 py-4 rounded-full font-medium transition-colors text-base inline-block">
					Request a Demo
				</a>
				<a href="#waitlist" class="bg-white/10 hover:bg-white/20 border border-white/10 text-white px-8 py-4 rounded-full font-medium transition-colors text-base inline-block">
					Join Waitlist
				</a>
			</div>
		</div>
	</div>

	<!-- Hero Image Container with Perspective -->
	<div class="relative w-full max-w-[1400px] mx-auto px-6 perspective-container">
		<div class="relative transform-3d hero-image-container origin-top opacity-90 hover:opacity-100 transition-opacity duration-700">
			<!-- Mobile App Mockup -->
			<div class="rounded-xl overflow-hidden border border-white/10 shadow-2xl bg-[#0a0a0a] aspect-[16/10] relative">
				<!-- Top bar -->
				<div class="h-10 bg-[#111] border-b border-white/5 flex items-center px-4 gap-2">
                    <div class="flex gap-2">
                        <div class="w-3 h-3 rounded-full bg-red-500/20"></div>
                        <div class="w-3 h-3 rounded-full bg-yellow-500/20"></div>
                        <div class="w-3 h-3 rounded-full bg-green-500/20"></div>
                    </div>
                    <div class="mx-auto w-1/3 h-6 bg-white/5 rounded-md text-[10px] flex items-center justify-center text-gray-500 font-mono">
                        smart-operator.ai
                    </div>
				</div>
				<!-- Content Mockup - Voice Interface -->
				<div class="flex h-full items-center justify-center bg-gradient-to-br from-[#0a0a0a] to-[#111]">
                    <div class="text-center p-12 max-w-2xl">
                        <!-- Voice Activation Visual -->
                        <div class="mb-12 relative">
                            <div class="w-32 h-32 mx-auto rounded-full bg-primary-500/20 border-2 border-primary-500/40 flex items-center justify-center relative">
                                <div class="absolute inset-0 rounded-full bg-primary-500/10 animate-ping"></div>
                                <svg class="w-16 h-16 text-primary-400 relative z-10" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11a7 7 0 01-7 7m0 0a7 7 0 01-7-7m7 7v4m0 0H8m4 0h4m-4-8a3 3 0 01-3-3V5a3 3 0 116 0v6a3 3 0 01-3 3z" />
                                </svg>
                            </div>
                        </div>
                        
                        <!-- Voice Command -->
                        <div class="mb-8">
                            <div class="inline-block bg-white/5 border border-white/10 rounded-full px-6 py-3 mb-4">
                                <span class="text-primary-400 font-semibold">"Hey, Ops"</span>
                            </div>
                            <p class="text-gray-400 text-lg">Voice-activated operational guidance</p>
                        </div>

                        <!-- Example Query -->
                        <div class="bg-[#1a1a1a] border border-white/10 rounded-xl p-6 text-left">
                            <div class="text-sm text-gray-500 mb-2">Operator asking:</div>
                            <div class="text-white mb-4">"What's the check-in procedure for VIP guests?"</div>
                            <div class="h-px bg-white/10 mb-4"></div>
                            <div class="text-sm text-primary-400">Providing contextual guidance...</div>
                        </div>
                    </div>
                </div>

				<!-- Gradient Overlay -->
				<div class="absolute inset-0 bg-gradient-to-t from-black/40 via-transparent to-transparent pointer-events-none"></div>
			</div>
		</div>
	</div>
    
    <!-- Available On -->
    <div class="max-w-[1400px] mx-auto px-6 mt-20 text-center">
        <p class="text-gray-500 text-sm mb-6 uppercase tracking-wider">Available on</p>
        <div class="flex flex-wrap justify-center items-center gap-12 opacity-60">
            <div class="flex items-center gap-3">
                <svg class="w-8 h-8" viewBox="0 0 24 24" fill="currentColor">
                    <path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.81-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/>
                </svg>
                <span class="text-lg font-semibold">iOS</span>
            </div>
            <div class="flex items-center gap-3">
                <svg class="w-8 h-8" viewBox="0 0 24 24" fill="currentColor">
                    <path d="M17.523 15.341c-.813-.802-.823-2.111-.011-2.929l.011-.012a2.09 2.09 0 0 0 0-2.953L6.476 2.935A.958.958 0 0 0 5.12 3.82v16.36a.958.958 0 0 0 1.356.885l11.047-6.512a2.09 2.09 0 0 0 0-2.953l-.011-.012z"/>
                </svg>
                <span class="text-lg font-semibold">Android</span>
            </div>
        </div>
    </div>
</section>

<style>
	.perspective-container {
		perspective: 2000px;
	}
	.transform-3d {
		transform: rotateX(20deg) scale(0.9);
        transform-style: preserve-3d;
	}
</style>
