<template>
  <div class="tab">
    <router-link class="tab-item" to="/recommend">
      <span class="tab-link">推荐</span>
    </router-link>
    <router-link class="tab-item" to="/singer">
      <span class="tab-link">歌手</span>
    </router-link>
    <router-link class="tab-item" to="/rank">
      <span class="tab-link">排行</span>
    </router-link>
    <router-link class="tab-item" to="/search">
      <span class="tab-link">搜索</span>
    </router-link>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="stylus">
@import "~common/stylus/variable";
.tab
  display : flex
.tab .tab-item{
  color : $color-theme;
  flex : 1;
  text-align : center;
  line-height : 2rem;
  text-decoration: none;
  margin : 0 20px;
  &.router-link-active{
    border-bottom: 1px solid $color-theme;
  }
}
</style>



