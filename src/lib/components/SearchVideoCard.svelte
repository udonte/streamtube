<script>
  import vidThumbnail from '$lib/assets/thumbnail.webp'
  import Avatar from '$lib/icons/avatar.png'
</script>

<a href="/" class="flex gap-4">
  <img class="max-w-[360px] object-cover aspect-video rounded-2xl w-full" src={vidThumbnail} alt="">

  <div class="text-gray-700">
    <h1 class="capitalized font-medium text-lg text-black">Enjoy the show</h1>
    <p class="text-sm mb-1">10mil . 2 hrs ago</p>
    <div class="flex items-center gap-2my-4">
      <img src={Avatar} alt="avatar" class="w-6 h-6 rounded-full">
      <p class="capitalize text-xs">lawal</p>
    </div>
    
    <p class="text-xs">
      Welcome to my channel
    </p>
    
    <div class="flex items-center gap-2 mt-3">
      <p class="rounded bg-green-100 text-gray-800 text-xs font-semibold py-0.5 px-1">4k</p>
      <p class="rounded bg-green-100 text-gray-800 text-xs font-semibold py-0.5 px-1">4k</p>
      <p class="rounded bg-green-100 text-gray-800 text-xs font-semibold py-0.5 px-1">4k</p>
    </div>
  </div>
</a>