<template>
  <div class="container">
    <input type="text" placeholder="what's good, user?" class="input-form" />
    <img src="@/assets/search.png" class="search-icon" />
  </div>
</template>

<script>
export default {
  name: "TweetBar",
};
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: row;
  align-items: center;
  width: 300px;
  height: auto;
  position: relative;
}

.input-form {
  box-sizing: border-box;
  width: 100%;
  height: 100%;
  border: 1px solid white;
  border-radius: 20px;
  padding: 10px;
  z-index: 0;
}

.search-icon {
  box-sizing: border-box;
  width: 40px;
  height: 100%;
  background-color: white;
  border-radius: 20px;
  position: absolute;
  right: 0px;
  z-index: 1;
  border: 1px solid #1d9bf0;
  cursor: pointer;
}
</style>
