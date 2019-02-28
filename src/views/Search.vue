<template>
  <div class="wrapper">
    <div class="search">
        <input name="search" />
    </div>
  </div>
</template>

<script>
export default {
  name: 'Search',
};
</script>
<style lang="scss" scoped>
    .wrapper {
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 100%;
        margin: 0;
        padding: 30px;
    }
</style>
