<template>
  <div class="home">
    <van-button url="/about" type="primary">朴素按钮</van-button>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  components: {},
})
export default class Home extends Vue {}
</script>
