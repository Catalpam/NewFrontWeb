<template>
  <div class="hello">
    <h2>{{this.$route.params.diarydate.split("-").slice(1).join("月") + "日"}}的每日瞎写</h2>
    <h3>Holy craft！这天本人似乎是摸鱼了，什么都没有写呢！</h3>
  </div>
</template>

<script>
export default {
  name: "diaryView",
};
</script>