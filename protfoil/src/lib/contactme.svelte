<script>

	import Icon from "@iconify/svelte";

</script>
<div class="flex flex-wrap gap-4 mb-10 mt-10">
	<!-- Google Button -->
       <a href="mailto:rachidzaaf9@gmail.com?subject=Your%20Subject%20Here" class="btn  gap-2 md:btn-lg w-full md:w-fit variant-filled-surface">
        <Icon icon="uim:google" />&nbsp; Send Email
       </a>
       
	<!-- Twitter Button -->
	<button class="btn variant-filled-surface gap-2"><Icon icon="mdi:twitter" />Follow on Twitter</button>

	<!-- Github Button -->
	<button class="btn bg-black text-white hover:opacity-70 gap-2"
		><Icon icon="mdi:github" />Login with Github</button
	>

	<!-- Facebook Button -->
	<button class="btn text-white gap-2" style="background-color: #4267B2;"
		><Icon icon="icon-park-outline:telegram" />Continue with Facebook
        https://t.me/raraeded09</button
	>

	<!-- Discord Button -->
	<button class="btn gap-2 text-white" style="background-color: #5865F2"
		><Icon icon="ic:baseline-discord" />Join Discord community</button
	>
</div>