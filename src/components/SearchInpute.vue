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
    text-align: center;
    font-size: 20px;
    font-weight: 300;
    color: white;
    height: 30px;
    border: 0;
    background: none;
    border-bottom: 1px solid white;
    transition: box-shadow .3s ease-out;
  }

  input:focus {
    outline: none;
    box-shadow: 0 5px 20px -8px rgba(255, 255, 255, .5);
  }
</style>
