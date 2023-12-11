<script lang="ts">
	import streamtubelogo from '$lib/icons/streamtubeLogo.png';
	import burgerIcon from '$lib/icons/bugerIcon.svg';
	import createIcon from '$lib/icons/createIcon.svg';
	import notificationIcon from '$lib/icons/notIcon.svg'
	import avatar from '$lib/icons/avatar.png'
	import SearchBar from './SearchBar.svelte';
	
</script>

<header class="flex items-center px-4 h-[64px] py-2 bg-white z-10 justify-between sticky top-0 left-0">
	<!-- sm size logo -->
	<a href="/" class="md:hidden mr-5">
		<div class="flex items-center justify-center gap-1 p-2">
			<img src={streamtubelogo} alt="streamtube" />
			<span class="font-bold text-3xl text-gray-700">stream<span class="text-green-600">tube</span>
		</div>
	</a>

	<div class="md:flex hidden gap-4 items-center">
		<img src={burgerIcon} alt="burgerIcon" class=" cursor-pointer p-3 rounded-full hover:bg-gray-200"/>
		<!-- md-size logo -->
		<a href="/">
			<div class="flex items-center justify-center gap-1 p-2">
				<img src={streamtubelogo} alt="streamtube" />
				<span class="font-bold text-3xl text-gray-700">stream<span class="text-green-600">tube</span>
			</div>
		</a>
	</div>

	<SearchBar />

	<div class="md:flex hidden gap-3 items-center">
		<img src={createIcon} alt="createIcon" class=" cursor-pointer p-3 rounded-full hover:bg-green-100" />
	
		<img src={notificationIcon} alt="notIcon" class=" cursor-pointer p-3 rounded-full hover:bg-green-100" />

		<img src={avatar} alt="avatar" class="bg-gray-200 h-8 w-8 rounded-full cursor-pointer">
	</div>
</header>
