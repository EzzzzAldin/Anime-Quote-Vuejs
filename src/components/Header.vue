<template>
  <header>
    <span class="highlight">{{ title }}</span>
  </header>
</template>

<script>
export default {
  props: ["title"],
};
</script>

<style scoped lang="scss">
header {
  padding: 24px 32px;
  display: flex;
  justify-content: center;
  span {
    color: #fff;
    font-size: 4rem;
    font-weight: 600;
    text-align: center;
    font-family: Comic Sans MS, Comic Sans, cursive;
  }
}
.highlight {
  background: url("../assets/brush-stroke-banner-3.png");
  background-repeat: no-repeat;
  background-size: 100% 95%;
  padding: 8px 0;
}
</style>
