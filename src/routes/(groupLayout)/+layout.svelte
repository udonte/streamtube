<script>
	import SideBar from "$components/SideBar.svelte";

</script>


<div class="flex">
	<SideBar />
	<main class="ml-[74px] flex-1 p-6">
		<slot />
	</main>
</div>