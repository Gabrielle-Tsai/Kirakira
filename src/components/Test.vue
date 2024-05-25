<template>
    <div class="test">
        我是測試元件中的內容 {{msg}}
    </div>
</template>

<script>
export default {
    data () {
        return {
            msg: '數據'
        }
    }
}
</script>

<style>
    .test {
        color: rosybrown;
    }
</style>