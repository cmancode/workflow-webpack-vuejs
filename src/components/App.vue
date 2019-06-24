<template>
    <main>
        <h1>{{ title }}</h1>
    </main>
</template>

<script>
export default {
    data(){
        return {
            title: 'Start to work here!!',
        }
    }
}
</script>

<style lang="scss">
    main{
        h1{
            position: absolute;
            color: burlywood;
            left: 50%;
            top: 50%;
            transform: translate(-50%, -50%);
        }
    }
    body{
        background: #121212;
    }
</style>
