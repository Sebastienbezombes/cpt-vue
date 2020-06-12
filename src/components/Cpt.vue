<template>
<div>
    <h1>{{ count }}</h1>
    <button @click="lessValue()">-</button>
    <button @click="addValue()">+</button>
</div>
</template>

<script>

export default {
    name:"Cpt",
    props: {
        count: Number
    },
    methods: {
        lessValue() {
            this.count = this.count-=1;
        },
        addValue() {
            this.count = this.count+=1;
        }
    }
}
</script>

<style scoped>
    button:nth-of-type(1) {
        margin-right: 16px;
    }
</style>