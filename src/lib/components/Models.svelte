<script lang="ts">
    import { Check } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="grid grid-cols-1 lg:grid-cols-2 gap-20 items-center">
            <!-- UI Mockup -->
			<div class="bg-[#0f0f0f] rounded-xl p-12 border border-white/5 relative overflow-hidden h-[600px] flex items-center justify-center">
                <div class="w-full max-w-sm bg-gradient-to-br from-[#1a1a1a] to-[#0a0a0a] rounded-xl shadow-2xl overflow-hidden text-white border border-white/10">
                    <div class="p-6 border-b border-white/10">
                        <div class="text-sm font-semibold mb-1">AI Capabilities</div>
                        <div class="text-xs text-gray-400">Multi-modal operational intelligence</div>
                    </div>
                    
                    <div class="p-4 space-y-3">
                        <div class="flex items-start gap-3 p-4 bg-primary-500/10 border border-primary-500/20 rounded-lg">
                            <div class="w-8 h-8 rounded-full bg-primary-500/20 flex items-center justify-center shrink-0 mt-1">
                                <svg class="w-4 h-4 text-primary-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11a7 7 0 01-7 7m0 0a7 7 0 01-7-7m7 7v4m0 0H8m4 0h4m-4-8a3 3 0 01-3-3V5a3 3 0 116 0v6a3 3 0 01-3 3z" />
                                </svg>
                            </div>
                            <div class="flex-1">
                                <div class="text-sm font-medium mb-1">Voice Recognition</div>
                                <div class="text-xs text-gray-400">Natural language understanding with "Hey, Ops" activation</div>
                            </div>
                        </div>

                        <div class="flex items-start gap-3 p-4 bg-white/5 border border-white/10 rounded-lg">
                            <div class="w-8 h-8 rounded-full bg-white/10 flex items-center justify-center shrink-0 mt-1">
                                <svg class="w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z" />
                                </svg>
                            </div>
                            <div class="flex-1">
                                <div class="text-sm font-medium mb-1">Computer Vision</div>
                                <div class="text-xs text-gray-400">Visual context awareness for situational guidance</div>
                            </div>
                        </div>
                        
                        <div class="flex items-start gap-3 p-4 bg-white/5 border border-white/10 rounded-lg">
                            <div class="w-8 h-8 rounded-full bg-white/10 flex items-center justify-center shrink-0 mt-1">
                                <svg class="w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z" />
                                </svg>
                            </div>
                            <div class="flex-1">
                                <div class="text-sm font-medium mb-1">Contextual AI</div>
                                <div class="text-xs text-gray-400">Personalized responses based on role and situation</div>
                            </div>
                        </div>

                        <div class="flex items-start gap-3 p-4 bg-white/5 border border-white/10 rounded-lg">
                            <div class="w-8 h-8 rounded-full bg-white/10 flex items-center justify-center shrink-0 mt-1">
                                <svg class="w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 4v5h.582m15.356 2A8.001 8.001 0 004.582 9m0 0H9m11 11v-5h-.581m0 0a8.003 8.003 0 01-15.357-2m15.357 2H15" />
                                </svg>
                            </div>
                            <div class="flex-1">
                                <div class="text-sm font-medium mb-1">Self-Learning</div>
                                <div class="text-xs text-gray-400">Knowledge base evolves with operator interactions</div>
                            </div>
                        </div>
                    </div>
                </div>
			</div>

            <!-- Text Content -->
			<div>
				<h2 class="text-4xl md:text-5xl lg:text-6xl font-normal mb-6 leading-tight">
					Multi-modal AI<br />
					for operational excellence
				</h2>
				<p class="text-gray-400 text-lg max-w-md">
					Computer vision, voice recognition, and conversational AI work together to understand context and deliver precise guidance.
				</p>
			</div>
		</div>
	</div>
</section>
