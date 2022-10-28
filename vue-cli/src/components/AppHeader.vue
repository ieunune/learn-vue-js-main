<!-- 파일 이름 명명 규칙은 PascalCase, 두 단어 이상 결합할 것 -->
<template>
    <header>
        <h1>{{ propsdata }}</h1>
        <button v-on:click="sendEvent">send</button>
    </header>
</template>

<script>
export default {
    props: ['propsdata'],
    methods: {
        sendEvent : function() {
            this.$emit('renew');
        }
    }
}
</script>

<style>

</style>