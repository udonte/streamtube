<script lang="ts">
  let showMore = false;
</script>

<div 

class:h-fit={showMore}
class:h-[105px]={!showMore}

class="bg-gray-100 mb-5 group relative overflow-hidden text-sm rounded-lg hover:bg-gray-200 p-3">
  <div class="font-medium mb-2">
    <span>10,000 views . 20-11-20</span>
  </div>

  <p class="mb-5">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Provident praesentium sed molestias consectetur amet velit commodi porro ipsam ex ipsa, repudiandae asperiores nihil reiciendis. Obcaecati esse minima temporibus adipisci commodi.Lorem ipsum dolor sit amet consectetur, adipisicing elit. Provident praesentium sed molestias consectetur amet velit commodi porro ipsam ex ipsa, repudiandae asperiores nihil reiciendis. Obcaecati esse minima temporibus adipisci commodi.Lorem ipsum dolor sit amet consectetur, adipisicing elit. Provident praesentium sed molestias consectetur amet velit commodi porro ipsam ex ipsa, repudiandae asperiores nihil reiciendis. Obcaecati esse minima temporibus adipisci commodi. </p>
  <button on:click={() => {
    showMore = !showMore;
  }} class="absolute bottom-1 group-hover:bg-gray-200 right-1 rounded-md bg-transparent font-medium p-1 capitalize">show {showMore ? 'more' : 'less'}</button>
</div>