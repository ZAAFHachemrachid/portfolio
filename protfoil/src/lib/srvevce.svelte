<script lang="ts">
	//import IconGauge from 'virtual:icons/tabler/gauge'
	//import IconUser from 'virtual:icons/tabler/user'
	//import IconCookie from 'virtual:icons/tabler/cookie'
	//import IconLock from 'virtual:icons/tabler/lock'
	//import IconMessage2 from 'virtual:icons/tabler/message-2'
    import type { SvelteComponentTyped } from "svelte";
	import Icon from '@iconify/svelte';


	const mockdata = [
		{
			title: 'Extreme performance',
			description:
				'This dust is actually a powerful poison that will even make a pro wrestler sick, Regice cloaks itself with frigid air of -328 degrees Fahrenheit',
		},
		{
			title: 'Privacy focused',
			description:
				'People say it can run at the same speed as lightning striking, Its icy body is so cold, it will not melt even if it is immersed in magma',
		},
		{
			title: 'No third parties',
			description:
				'They’re popular, but they’re rare. Trainers who show them off recklessly may be targeted by thieves',
			
		},
		{
			
			title: 'Secure by default',
			description:
				'Although it still can’t fly, its jumping power is outstanding, in Alola the mushrooms on Paras don’t grow up quite right'
		}
	]
</script>

<div class="container mx-auto max-w-screen-lg">
	<div class="grid grid-cols-1 md:grid-cols-12">
		<div class="space-y-4 md:col-span-4 p-4">
			<div class="text-xl md:text-3xl font-bold">
				Integrate effortlessly with any technology stack
			</div>
			<p class="max-w-xl opacity-60 mx-auto">
				Every once in a while, you’ll see a Golbat that’s missing some fangs. This happens when
				hunger drives it to try biting a Steel-type Pokémon.
			</p>
			<button class="btn md:btn-lg variant-filled-tertiary">Get Started</button>
		</div>
		<div class="grid grid-cols-1 md:grid-cols-2 gap-4 md:col-span-8">
				<div class="p-4 space-y-2">
					<div class="variant-filled-tertiary text-2xl p-2 w-fit rounded-token">
                        <Icon icon="iconoir:network-solid" />
					</div>

					<div class="font-semibold">
                        Extreme performance
					</div>
					<div class="text-sm opacity-60">
                        This dust is actually a powerful poison that will even make a pro wrestler sick, Regice cloaks itself with frigid air of -328 degrees Fahrenheit
					</div>
				</div>
                <div class="p-4 space-y-2">
					<div class="variant-filled-tertiary text-2xl p-2 w-fit rounded-token">
                        <Icon icon="carbon:network-2" />
					</div>

					<div class="font-semibold">
                        Extreme performance
					</div>
					<div class="text-sm opacity-60">
                        This dust is actually a powerful poison that will even make a pro wrestler sick, Regice cloaks itself with frigid air of -328 degrees Fahrenheit
					</div>
				</div>
                <div class="p-4 space-y-2">
					<div class="variant-filled-tertiary text-2xl p-2 w-fit rounded-token">
                        <Icon icon="codicon:terminal-linux" />					
                    </div>

					<div class="font-semibold">
                        Extreme performance
					</div>
					<div class="text-sm opacity-60">
                        This dust is actually a powerful poison that will even make a pro wrestler sick, Regice cloaks itself with frigid air of -328 degrees Fahrenheit
					</div>
				</div>
                <div class="p-4 space-y-2">
					<div class="variant-filled-tertiary text-2xl p-2 w-fit rounded-token">
                        <Icon icon="carbon:gui" />				
                    </div>

					<div class="font-semibold">
                        Extreme performance
					</div>
					<div class="text-sm opacity-60">
                        This dust is actually a powerful poison that will even make a pro wrestler sick, Regice cloaks itself with frigid air of -328 degrees Fahrenheit
					</div>
				</div>
		</div>
	</div>
</div>