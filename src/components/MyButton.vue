<template>
    <div>
        <h2>我爱你</h2>
        <button @click="count++">爱了{{count}}次</button>
    </div>
</template>

<script>
export default {
    data(){
        return{
            count:0
        }
    }
}
</script>

<style>
    h2{
        color: aquamarine;
    }
</style>