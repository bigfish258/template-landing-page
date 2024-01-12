<script setup lang="ts">
  const online = useOnline()
  useSeoMeta({
    title: 'Dream AI',
    description: 'Unleashing the Power of Artificial Intelligence to Transform Your Digital Experience',
  })

  defineOgImage({
    title: 'Dream AI',
    description: 'Revolutionizing the Web with Cutting-Edge AI Solutions, Offering Unparalleled User Experiences and Smart, Data-Driven Insights for a Smarter Digital Future',
  })
</script>

<template>
  <Home />
</template>
