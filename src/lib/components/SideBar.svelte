<script lang="ts">
  import homeIcon from '$lib/icons/homeIcon.svg'
  import shortsIcon from '$lib/icons/shortsIcon.svg'
  import libraryIcon from '$lib/icons/libraryIcon.svg'
  import subIcon from '$lib/icons/subIcon.svg'
  

  const nav = [
    {
    icon: homeIcon,
    title: 'home'
  },
  {
    icon: shortsIcon,
    title: 'shorts'
  },
  {
    icon: libraryIcon,
    title: 'library'
  },
  {
    icon: subIcon,
    title: 'subscription'
  },

]

</script>

<div class="bg-white py-2 flex flex-col px-1 fixed top-[60px]">
 
    {#each nav as navItem}
    <a href="/" class="flex items-center justify-center flex-col gap-1 py-4 hover:bg-green-100 rounded-lg">
    <img src={navItem.icon} alt="">
    <p>{navItem.title}</p>
  </a>
    {/each}
</div>