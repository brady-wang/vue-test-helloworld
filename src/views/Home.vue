<template>
  <div>
    <HelloWorld msg="home page"></HelloWorld>
    <Brady msg="home page"></Brady>
  </div>
</template>

<script>
// 引入两个公共的组件
import HelloWorld from "../components/HelloWorld"
import Brady from "../components/Brady"

// 导出组件
export default {
  name: 'Home',
  components: {
    Brady,
    HelloWorld
  }
}
</script>
