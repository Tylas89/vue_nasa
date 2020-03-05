<template>
    <div class="searchWrapper">
      <input id="search" name="search" v-model="searchValue" @input="handlerInput" />
    </div>
</template>
<script>
export default {
  name: 'SchareInput',
};
</script>
<style lang="scss" scoped>
  .searchWrapper{
    margin-top: 50px;
    display: flex;
    flex-direction: column;
    width:250px;
  }

  input {
    height: 30px;
    border: 0;
    background: none;
    border-bottom: 1px solid black;
  }
</style>
