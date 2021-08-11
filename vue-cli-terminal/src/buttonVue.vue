<template>
    <div @click="click" >
        Click { {count} } times
    </div>
</template>

<script>
export default {
    name: buttonVue,
    data() {
        return {
            count: 0,
        };
    },
    methods: {
        click() {
            this.count++;
        },
    },
}
</script>