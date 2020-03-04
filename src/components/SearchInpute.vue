<template>
    <div class="searchWrapper">
      <label for="search">Search</label>
      <input id="search" name="search" v-model="searchValue" @input="handlerInput" />
    </div>
</template>
<script>
export default {
    name: 'SchareInput',
};
</script>
<style lang="scss" scoped>

</style>