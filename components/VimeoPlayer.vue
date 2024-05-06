<template>
  <div :style="'padding:75% 0 0 0;position:relative;'">
    <iframe :src="'https://player.vimeo.com/video/' + videoId + '?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479'" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write" style="position:absolute;top:0;left:0;width:100%;height:100%;" :title="'Vimeo video ' + videoId"></iframe>
  </div>
</template>

<script>
export default {
  name: 'VimeoPlayer',
  props: {
    videoId: {
      type: String,
      required: true
    }
  }
};
</script>

