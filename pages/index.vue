<template>
    <div>
        123456
    </div>
</template>
<script setup>
// Default
// const socket = useSocket()

// Custom
// const io = useIO()

const connected = ref(false)

// onMounted(() => {
//   socket.on('connect', () => {
//     connected.value = socket.connected
//   })

//   socket.on('disconnect', () => {
//     connected.value = socket.connected
//   })
// })
</script>

<template>
  <div>Connected: {{ connected }}</div>
</template>