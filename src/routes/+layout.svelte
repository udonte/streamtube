<script lang="ts">
	import "../app.pcss";
	import Header from '$lib/components/Header.svelte'
	import SideBar from "$components/SideBar.svelte";

  
</script>
<Header />
<div class="flex">
	<SideBar />
	<main class="ml-[74px] p-6">
		<slot></slot>
	</main>
</div>
