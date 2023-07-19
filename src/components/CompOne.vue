<template>
    <slot :firstName="data" name="firstSlot"></slot>
    <slot :secondName="data2" name="secondSlot"></slot>
</template>

<script>
export default {
    data() {
        return {
            data: "This is Data.",
            data2: "This is Data2."
        }
    }
}
</script>