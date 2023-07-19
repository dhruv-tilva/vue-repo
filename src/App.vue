<template>
  <comp-one v-slot:firstSlot="receiveData">
    <h1>{{ receiveData.firstName }}</h1>
  </comp-one>

  <comp-one v-slot:secondSlot="receiveData2">
    <h1>{{ receiveData2.secondName }}</h1>
    <h2>Hello World</h2>
  </comp-one>
</template>

<script>
import CompOne from "./components/CompOne.vue"
export default {
  components: { CompOne }
}
</script>
