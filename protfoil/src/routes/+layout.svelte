<script lang="ts">
	import '../app.postcss';
	import { AppShell, AppBar } from '@skeletonlabs/skeleton';

   import type { AfterNavigate } from '@sveltejs/kit';
   import { afterNavigate } from '$app/navigation';

afterNavigate((params: AfterNavigate) => {
    const isNewPage = params.from?.url.pathname !== params.to?.url.pathname;
    const elemPage = document.querySelector('#page');
    if (isNewPage && elemPage !== null) {
        elemPage.scrollTop = 0;
    }
});

</script>

<!-- App Shell -->
<AppShell scrollbarGutter="auto" >
	<svelte:fragment slot="header">
		<!-- App Bar -->
		<AppBar>
			<svelte:fragment slot="lead">
				<strong class="text-xl uppercase">Rachid</strong>
			</svelte:fragment>
			<svelte:fragment slot="trail">
				<a
					class="btn btn-sm variant-ghost-surface"
					href="#" 
				>
					Services 
				</a>
				<a
					class="btn btn-sm variant-ghost-surface"
					href="#" 
				>
					Projects
				</a>
				<a
					class="btn btn-sm variant-ghost-surface"
					href="#" 
				>
					Contact
				</a>
			</svelte:fragment>
		</AppBar>
	</svelte:fragment>
	
	<!-- Page Route Content -->
	<slot />
	<svelte:fragment slot="pageFooter">

		<footer class="bg-surface-300-600-token p-4">
			<div class="container mx-auto">
				<div class="flex items-center justify-between">
					<div>
						<p class="text-sm text-surface-300-900-token">© 2021 Rachid</p>
					</div>
					<div>
						<a href="#" class="text-sm text-surface-300-900-token">Privacy Policy</a>
						<a href="#" class="text-sm text-surface-300-900-token">Terms of Service</a>
					</div>
				</div>
			</div>
		</footer>
	</svelte:fragment>
</AppShell>
