<template>
    <div style="flex:1">
        <studyGarden></studyGarden>
    </div>
</template>

<!--引入bui-weex样式文件-->
<style lang="scss" src="bui-weex/src/css/buiweex.scss"></style>

<script>
    import studyGarden from "./studyGarden.vue";
    module.exports = {
        data () {
            return {}
        },
        components: {
          studyGarden
        }
    }
</script>