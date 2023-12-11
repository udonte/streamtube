<script>
  import searchIcon from '$lib/icons/searchIcon.svg'
</script>

<form class="flex h-[40px] basis-[600px]">
  <input class="h-[40px] outline-none border-[2px] border-e-0 rounded-s-3xl focus:border-green-200 focus:border-[2px] px-3 flex-1 border-gray-100" type="text">
  <button class="flex items-center justify-center cursor-pointer w-16 bg-green-100 rounded-e-3xl">
    <img src={searchIcon} alt="searchIcon">
  </button>
</form>