<script lang="ts">
    import { Play } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="text-center mb-20">
			<h2 class="text-4xl md:text-5xl lg:text-6xl font-normal mb-6">
				The Operator Performance<br />
				System for hospitality
			</h2>
			<p class="text-gray-400 text-lg max-w-2xl mx-auto">
				Beyond traditional LMS. Transform static procedures into dynamic, voice-activated operational tools.
			</p>
		</div>

		<!-- Row 1 -->
		<div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
			<!-- Card 1: Voice Activation -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[600px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Voice-Activated</h3>
					<p class="text-gray-400 text-sm">Hands-free access with "Hey, Ops" wake word</p>
				</div>
                
                <!-- Mockup Content -->
                <div class="flex-1 relative flex items-center justify-center">
                    <div class="text-center">
                        <!-- Voice Wave Animation -->
                        <div class="w-48 h-48 mx-auto rounded-full bg-primary-500/10 border-2 border-primary-500/30 flex items-center justify-center relative mb-8">
                            <div class="absolute inset-0 rounded-full bg-primary-500/20 animate-ping"></div>
                            <svg class="w-24 h-24 text-primary-400 relative z-10" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11a7 7 0 01-7 7m0 0a7 7 0 01-7-7m7 7v4m0 0H8m4 0h4m-4-8a3 3 0 01-3-3V5a3 3 0 116 0v6a3 3 0 01-3 3z" />
                            </svg>
                        </div>
                        <div class="bg-white/5 border border-white/10 rounded-full px-8 py-4 inline-block">
                            <span class="text-primary-400 font-semibold text-xl">"Hey, Ops"</span>
                        </div>
                        <p class="text-gray-500 text-sm mt-4">Always listening, always ready</p>
                    </div>
                </div>
			</div>

			<!-- Card 2: Living SOPs -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[600px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Living SOPs</h3>
					<p class="text-gray-400 text-sm">Dynamic procedures that evolve with your operations</p>
				</div>
                
                <!-- Mockup Content -->
                <div class="flex-1 relative bg-[#0a0a0a] rounded-lg border border-white/5 overflow-hidden p-6 flex flex-col">
                    <!-- SOP Document -->
                    <div class="space-y-4">
                        <div class="flex items-center justify-between">
                            <div class="text-sm font-semibold text-white">VIP Check-In Procedure</div>
                            <div class="text-xs text-primary-400 flex items-center gap-1">
                                <div class="w-2 h-2 rounded-full bg-primary-400 animate-pulse"></div>
                                Live
                            </div>
                        </div>
                        
                        <div class="space-y-3">
                            <div class="bg-white/5 p-3 rounded border-l-2 border-primary-500">
                                <div class="text-xs text-gray-400 mb-1">Step 1</div>
                                <div class="text-sm text-gray-300">Greet guest by name</div>
                            </div>
                            <div class="bg-white/5 p-3 rounded border-l-2 border-primary-500">
                                <div class="text-xs text-gray-400 mb-1">Step 2</div>
                                <div class="text-sm text-gray-300">Verify reservation details</div>
                            </div>
                            <div class="bg-white/5 p-3 rounded border-l-2 border-white/20 opacity-50">
                                <div class="text-xs text-gray-400 mb-1">Step 3</div>
                                <div class="text-sm text-gray-300">Explain amenities</div>
                            </div>
                        </div>

                        <div class="mt-6 bg-primary-500/10 border border-primary-500/20 rounded-lg p-4">
                            <div class="text-xs text-primary-400 mb-2">💡 Recent Update</div>
                            <div class="text-xs text-gray-300">Added personalized welcome gift protocol</div>
                        </div>
                    </div>
                </div>
			</div>
		</div>

        <!-- Row 2 -->
		<div class="grid grid-cols-1 md:grid-cols-3 gap-6">
			<!-- Card 3: Knowledge Capture -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Knowledge Capture</h3>
					<p class="text-gray-400 text-sm">Preserve institutional memory and expertise</p>
				</div>
                
                 <!-- Mockup Content - Code Editor Look -->
                <div class="flex-1 relative bg-[#0a0a0a] rounded-lg border border-white/5 overflow-hidden p-4 font-mono text-[10px] leading-relaxed text-gray-400 shadow-inner">
                    <div class="flex gap-1.5 mb-4 border-b border-white/5 pb-2">
                        <div class="w-2 h-2 rounded-full bg-red-500/50"></div>
                        <div class="w-2 h-2 rounded-full bg-yellow-500/50"></div>
                        <div class="w-2 h-2 rounded-full bg-green-500/50"></div>
                    </div>
                    <div class="space-y-1">
                        <div class="text-purple-400">from <span class="text-white">future_import</span> import <span class="text-yellow-300">annotations</span></div>
                        <div class="text-purple-400">from <span class="text-white">typing</span> import <span class="text-yellow-300">List, Optional</span></div>
                        <br/>
                         <div class="text-purple-400">class <span class="text-yellow-300">DataAnalyzer</span>:</div>
                         <div class="pl-4 text-gray-600">"""Analyzer for processing large datasets"""</div>
                         <div class="pl-4 text-purple-400">def <span class="text-blue-400">__init__</span>(self, data: List[Any]):</div>
                         <div class="pl-8 text-white">self.data = data</div>
                         <div class="pl-8 text-white">self.processed = False</div>
                         <div class="pl-4 text-purple-400">def <span class="text-blue-400">analyze</span>(self):</div>
                         <div class="pl-8 text-white">if not self.data:</div>
                         <div class="pl-12 text-purple-400">return <span class="text-orange-400">None</span></div>
                    </div>
                </div>
			</div>

			<!-- Card 4: Contextual Guidance -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Contextual Guidance</h3>
					<p class="text-gray-400 text-sm">Right knowledge, right time, right person</p>
				</div>
                
                 <!-- Mockup Content - Action Card -->
                <div class="flex-1 relative flex items-center justify-center">
                    <div class="bg-[#1a1a1a] border border-white/10 rounded-xl p-5 w-full shadow-2xl relative">
                        <!-- Glow effect -->
                        <div class="absolute -inset-1 bg-gradient-to-r from-blue-500/20 to-purple-500/20 blur opacity-50"></div>
                        
                        <div class="relative bg-[#1a1a1a] rounded-xl">
                            <div class="flex items-center gap-3 mb-4">
                                <div class="w-8 h-8 rounded bg-white/10 flex items-center justify-center shrink-0">
                                    <div class="w-4 h-4 bg-white rotate-45"></div>
                                </div>
                                <div>
                                    <div class="font-medium text-xs text-white">Meeting with Vandelay Inc. finished</div>
                                    <div class="text-[10px] text-gray-500">Update Salesforce after meeting</div>
                                </div>
                            </div>
                            <div class="h-1.5 w-full bg-white/10 rounded-full overflow-hidden">
                                <div class="h-full bg-blue-500 w-2/3"></div>
                            </div>
                        </div>
                    </div>
                </div>
			</div>

            <!-- Card 5: Multi-Site Rollout -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Multi-Site Rollout</h3>
					<p class="text-gray-400 text-sm">Rapid deployment across 100K+ locations</p>
				</div>
                
                 <!-- Mockup Content - Search/Result -->
                <div class="flex-1 relative flex flex-col gap-4">
                    <div class="bg-[#1a1a1a] rounded-lg p-4 text-xs text-gray-300 border border-white/5">
                        Sure thing! Here's an overview I've made for you.
                    </div>
                    
                    <div class="flex-1 bg-gradient-to-br from-[#1a1a1a] to-black border border-white/10 rounded-lg overflow-hidden flex flex-col">
                         <div class="relative h-32 bg-gradient-to-r from-purple-500/20 to-blue-500/20 flex items-center justify-center">
                             <div class="text-center">
                                 <div class="text-xs font-semibold text-white">Personalized course</div>
                                 <div class="text-[10px] text-gray-400">8 cards</div>
                             </div>
                         </div>
                         <div class="p-4 flex items-center justify-between mt-auto">
                             <div class="text-[10px] text-gray-500">Updated 2m ago</div>
                             <button class="bg-white text-black text-[10px] font-bold px-3 py-1.5 rounded-full flex items-center gap-1 hover:bg-gray-200 transition-colors">
                                 <Play size={10} fill="currentColor" /> Play
                             </button>
                         </div>
                    </div>
                </div>
			</div>
		</div>
	</div>
</section>
