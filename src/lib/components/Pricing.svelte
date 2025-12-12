<script lang="ts">
    import { Check } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white border-t border-white/5">
	<div class="max-w-[1400px] mx-auto px-6">
		<h2 class="text-4xl font-normal mb-16">Pricing</h2>

		<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
			<!-- Enterprise -->
			<div class="border-r border-white/10 pr-8">
				<h3 class="text-xl font-bold mb-2">Enterprise</h3>
				<p class="text-gray-400 text-sm mb-6">Custom pricing per location</p>
				<a href="mailto:sales@smart-operator.ai" class="bg-white text-black px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-gray-200 transition-colors inline-block">
					Contact Sales
				</a>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">MULTI-SITE OPERATIONS</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-400 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Unlimited locations and operators</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-400 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Full PMS/POS integration suite</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-400 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Custom knowledge base migration</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-400 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Multi-site rollout coordination</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-400 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Advanced analytics & reporting</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-400 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Dedicated success manager & 24/7 support</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-400 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>SSO, SAML, and enterprise security</span>
					</li>
				</ul>
			</div>

			<!-- Growth -->
			<div class="border-r border-white/10 pr-8">
				<h3 class="text-xl font-bold mb-2">Growth</h3>
				<p class="text-primary-400 text-sm mb-6">Contact for pricing</p>
				<a href="#demo" class="bg-transparent border border-white/20 text-white px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-white/10 transition-colors inline-block">
					Request Demo
				</a>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">GROWING OPERATIONS</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-400 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Up to 10 locations</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-400 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Unlimited operators per location</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-400 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Voice-activated guidance</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-400 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Living SOPs & knowledge base</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-400 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Standard PMS/POS integrations</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-400 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Basic analytics dashboard</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-400 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Email & chat support</span>
					</li>
				</ul>
			</div>

			<!-- Pilot -->
			<div>
				<h3 class="text-xl font-bold mb-2">Pilot</h3>
				<p class="text-gray-400 text-sm mb-6">Join waitlist</p>
				<a href="#waitlist" class="bg-transparent border border-white/20 text-white px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-white/10 transition-colors inline-block">
					Join Waitlist
				</a>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">SINGLE LOCATION TRIAL</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-400 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Single location access</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-400 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Up to 25 operators</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-400 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Voice-activated guidance</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-400 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Core knowledge base features</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-400 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>iOS & Android apps</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-400 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>30-day pilot program</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-400 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Onboarding & training included</span>
					</li>
				</ul>
			</div>
		</div>
	</div>
</section>
