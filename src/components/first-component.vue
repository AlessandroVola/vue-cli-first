<template>
    <div>
        <div class="red" @click="saluta">Il mio primo componente JumboTron</div>
    </div>

</template>

<script>
export default {
    name: `FirstComponent`,
    methods: {
        saluta() {
            console.log(`saluto`)
        }
    }
}
</script>


<style scoped>
.red {
    background-color: red;
}
</style>