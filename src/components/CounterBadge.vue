<template>
  <span class="badge" v-if="count > 0">{{ count }}</span>
</template>
<script>
export default {
  name: "CounterBadge",
  props: ["count"]
};
</script>
<style lang="scss">
.badge {
  position: absolute;
  top: 2rem;
  right: 0.5rem;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 20px;
  width: 20px;
  border-radius: 20px;
  background-color: #42b983;
  color: #fff;
  font-weight: bold;
  font-size: 12px;
}
</style>