<script lang="ts">
import Avatar from '$lib/icons/avatar.png'
import LikeIcon from '$lib/icons/likeIcon.svg'
import Dislike from '$lib/icons/dislikeIcon.svg'

</script>

<div class="flex gap-4">
  <img src={Avatar} alt="avatar" class="w-10 h-10 rounded-full">
  <div class="space-y-2">
    <div class="flex items-baseline">
      <h1 class="font-medium text-sm capitalize">bonnie</h1>
      <span class="text-xs text-gray-600"> 12 hours ago</span>
    </div>
    <p class="text-sm">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum, nostrum! Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum, nostrum!</p>
    <div class="flex items-center gap-5">

      <button class="p-1 text-xs rounded-full hover:bg-gray-200">
        <img src={LikeIcon} alt="like">
      </button>

      <button class="p-1 text-xs rounded-full hover:bg-gray-200">
        <img src={Dislike} alt="dislike">
      </button>
      <button class="px-2 font-medium capitalize py-1 text-xs rounded-full hover:bg-gray-200 text-green-600">Reply</button>

    </div>

  </div>
</div>