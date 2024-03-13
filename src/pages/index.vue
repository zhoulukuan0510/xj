<template>
  <div>123</div>
</template>

<script setup>
import { reactive, toRefs, onBeforeMount, onMounted } from 'vue'
import { useRoute, useRouter } from 'vue-router'
const route = useRoute()
const router = useRouter()
const data = reactive({})
onBeforeMount(() => {
  console.log('2.组件挂载页面之前执行----onBeforeMount')
})
onMounted(() => {
  console.log('3.-组件挂载到页面之后执行-------onMounted')
})

</script>
<style scoped>
</style>