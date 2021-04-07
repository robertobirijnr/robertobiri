<template>
<div>
  <index/>
  <skills/>
  <recent-projects/>
</div>
</template>

<script>

import Skills from '../components/skills.vue'
import Index from '../components/header/index.vue'
import RecentProjects from '../components/recentProjects.vue'
export default {
  components: { Skills, Index,RecentProjects },}
</script>

<style>

</style>
