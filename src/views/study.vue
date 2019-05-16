<template>
  <div>
    <!-- 学习园地 -->
    <div class="study-field bra">
      <div class="study-field-title bb flex-jc">
        <text class=" f30 c6">学习园地</text>
      </div>
      <div class="study-plan flex-dr">
        <div class="study-schedule flex1 br flex-ac flex-jc">
          <div class="flex-dr flex-fe">
            <text class="f80">40</text>
            <text class="f30 pb10">%</text>
          </div>
          <text class="f30 c6">学习进度</text>
        </div>
        <div class="study-grade flex1 flex-ac flex-jc">
          <div class="flex-dr flex-fe">
            <text class="f80">30</text>
            <text class="f30 pb10">分</text>
          </div>
          <text class="f30 c6">已得学分</text>
        </div>
      </div>
      <div class="study-content flex-dr brb">
        <div class="flex1 flex-jc flex-ac brf" @click='hotClassEvent'>
          <text class="f30 c9">热门微课</text>
        </div>
        <div class="flex1 flex-jc flex-ac  brf" @click='classCenterEvent'>
          <text class="f30 c9">课程中心</text>
        </div>
        <div class="flex1 flex-jc flex-ac" @click='findMoreEvent'>
          <text class="f30 c9">发现更多</text>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    data() {
      return {}
    },
    methods: {
      // 热门课程
      hotClassEvent() {
        this.$alert('热门课程')
      },
      // 课程中心
      classCenterEvent() {
        this.$alert('课程中心')
      },
      // 发现更多
      findMoreEvent() {
        this.$alert('发现更多')
      }
    }
  }
</script>

<style lang="css" src="../css/common.css"></style>
<style>
  .study-field {
    background-color: #fff;
  }

  .study-field-title {
    padding: 0 20px;
    height: 100px;
  }

  .study-plan {
    height: 200px;
  }

  .study-content {
    height: 100px;
    background-color: #f2f2f2;
  }
</style>