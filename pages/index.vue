<template>
  <div>
    <the-banner></the-banner>
    <div v-for="(img, i) in imgs" :key="i">
      <the-post :img="img"></the-post>
    </div>
  </div>
</template>

<script lang="ts">
export default {
  data() {
    return {
      imgs: [
        "https://picsum.photos/id/1/200/300",
        "https://picsum.photos/id/2/200/300",
        "https://picsum.photos/id/3/200/300",
        "https://picsum.photos/id/4/200/300",
        "https://picsum.photos/id/5/200/300",
        "https://picsum.photos/id/6/200/300",
        "https://picsum.photos/id/7/200/300",
        "https://picsum.photos/id/8/200/300",
        "https://picsum.photos/id/9/200/300",
        "https://picsum.photos/id/10/200/300",
        "https://picsum.photos/id/11/200/300",
        "https://picsum.photos/id/12/200/300",
        "https://picsum.photos/id/13/200/300",
        "https://picsum.photos/id/14/200/300",
        "https://picsum.photos/id/15/200/300",
        "https://picsum.photos/id/16/200/300",
        "https://picsum.photos/id/17/200/300",
        "https://picsum.photos/id/18/200/300",
        "https://picsum.photos/id/19/200/300",
        "https://picsum.photos/id/20/200/300",
        "https://picsum.photos/id/21/200/300",
        "https://picsum.photos/id/22/200/300",
        "https://picsum.photos/id/23/200/300",
        "https://picsum.photos/id/24/200/300",
      ],
    }
  },
}
</script>

<style>
</style>