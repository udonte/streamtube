<script lang="ts">
  import Avatar from '$lib/icons/avatar.png'
  import LikeIcon from '$lib/icons/likeIcon.svg'
  import DislikeIcon from '$lib/icons/dislikeIcon.svg'
  import ShareIcon from '$lib/icons/shareIcon.svg'
  import MoreIcon from '$lib/icons/moreIcon.svg'
</script>

<div class="flex my-5 items-center justify-between">

  <div class="flex items-center gap-5">
    <!-- channel name and subscribe button -->
    <div class="flex items-center gap-3">
      <img src={Avatar} alt="avatar" class="w-10 h-10 rounded-full">
      <div>
        <p class="font-medium capitalize">George Sb</p>
        <p class="text-gray-700 text-xs">1000 subs</p>
      </div>
      <button class="bg-black text-white text-sm w-fit font-medium rounded-full py-2 px-4">Subscribe</button>
    </div>
    <div class="flex gap-3 items-center">
      <!-- like and dislike button -->
      <div class="divide-x-2 bg-green-100  flex items-center overflow-hidden rounded-full">
        <button class="py-2 px-4 flex items-center gap-2 hover:bg-green-200">
          <img src={LikeIcon} alt="like">
          <span class="text-sm font-medium">3000</span>
        </button>
        <button class="py-2 px-4 flex items-center gap-2 hover:bg-green-200">
          <img src={DislikeIcon} alt="like">
          <span class="text-sm font-medium">3000</span>
        </button>
      </div>

      <!-- share button -->
      <button class="py-2 px-4 flex items-center rounded-full gap-2 hover:bg-green-100">
        <img src={ShareIcon} alt="like">
        <span class="text-sm font-medium">Share</span>
      </button>

      <!-- more button -->
      <button class="p-2 flex items-center rounded-full gap-2 hover:bg-green-100">
        <img src={MoreIcon} alt="like">
      </button>


    </div>

  </div>

</div>