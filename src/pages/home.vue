<template>
    <div>
        <p>首页</p>
    </div>
</template>
<script type="text/ecmascript-6">
    export default {
        name: 'app',
        data() {
            return {
                num1: 1
            };
        },
        methods: {
            handleChange(value) {
                console.log(value);
            }
        }
    }
</script>

<style>

</style>
