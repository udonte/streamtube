<script lang="ts">
	import ChanelInfo from "$components/ChanelInfo.svelte";
	import Comments from "$components/Comments.svelte";
	import RecommendedVideos from "$components/RecommendedVideos.svelte";
	import VideoDescription from "$components/VideoDescription.svelte";

  let videoId = "GDHO_AiEVFAkZpXE";
</script>

<iframe 
  title="Streamtube video player" 
  class="w-full h-[480px]" 
  src={`https://youtube.com/embed/${videoId}`} 
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write encrypted-media; gyroscope; picture-in-picture; web-share"
  allowfullscreen
  >Offline</iframe>

  <div class="max-w-[1150px] px-2 w-full mx-auto">
    <h1 class="text-xl font-semibold">Svelte Rules</h1>

    <div class="flex flex-col md:flex-row gap-5 md:justify-between items-start">
      <div class="flex-1">
        <ChanelInfo />
        <VideoDescription />
        <Comments />
      </div>
      <RecommendedVideos />
    </div>
  </div>