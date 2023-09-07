<template>
  <div class="project__buttons_item">
    <slot />
  </div>
</template>

<script>
export default {
  name: "ButtonError",
  props: {
    text: Object,
  },
};
</script>

<style lang="scss" scoped>
.project__buttons_item {
  display: flex;
  padding: 26px 66px;
  justify-content: center;
  align-items: center;
  gap: 10px;

  border-radius: 18px;
  background: #fff;

  color: #292f36;
  text-align: center;
  font-family: Jost;
  font-size: 18px;
  font-style: normal;
  font-weight: 600;
  line-height: 125%;
  letter-spacing: 0.36px;

  &-active {
    background: #cda274;
    color: #fff;
  }
}
</style>
