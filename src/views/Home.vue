<template>
  <div class="home">
    111111222
    <Button type="primary">主要按钮</Button>
    <Button plain type="primary">朴素按钮</Button>
    <span class="aaaa">测试一下git</span>
  </div>
</template>

<script>
import { Button, Toast } from "vant";
export default {
  name: "home",
  components: {
    Button
  },
  created() {
    Toast("提示内容");
  }
};
</script>
<style lang="scss">
@import "./../styles/index.scss";
.home{
  color:red;
  .aaaa{
    color:green;
  }
}
</style>
