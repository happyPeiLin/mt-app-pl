<template>
  <div>
    <el-container class="layout-default">
      <el-header>
        <my-header />
      </el-header>
      <el-main>
        <nuxt />
      </el-main>
      <el-footer  height=100%>
        <my-footer/>
      </el-footer>
    </el-container>
  </div>
</template>

<script>
import MyHeader from '@/components/public/header/index.vue'
import MyFooter from '@/components/public/footer/index.vue'
export default {
  components: {
    MyHeader,
    MyFooter
  }
}
</script>

<style lang="scss">
  @import "@/assets/css/public/layout.scss";
</style>
