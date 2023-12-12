<script lang="ts">
  import vidThumbnail from '$lib/assets/thumbnail.webp'
  import avatar from '$lib/icons/avatar.png'

</script>

<a href="/">
  <div class="relative">
    <div class="absolute bottom-1 right-1 bg-black/80 text-white font-semibold rounded text-xs px-1">10:20</div>
    <img src={vidThumbnail} alt="video thumbnail" class="sm:h-[308px] h-[250px] w-full object-cover rounded-2xl bg-gray-200" />
  </div>
    
    <div class="flex gap-3 mt-3">
      <img src={avatar} alt="imageAvatar" class="h-9 w-9 rounded-full bg-green-100">
      <div>
      <h3 class="capitalize font-medium text-green-600">Video title</h3>
      <p class="text-gray-600 text-sm capitalize mt-1">George</p>
        
        <div class="text-gray-600 text-sm">
          <span>5 mil</span>
          <span>2hrs</span>
        </div>
      </div>
  </div>
</a>