<template>
<div>
  <index/>
  <skills/>
  <recent-projects/>
  <contact-us/>
</div>
</template>

<script>

import Skills from '../components/skills.vue'
import Index from '../components/header/index.vue'
import RecentProjects from '../components/recentProjects.vue'
import ContactUs from '../components/contact-us.vue'
export default {
  components: { Skills, Index,RecentProjects, ContactUs },}
</script>

<style>

</style>
