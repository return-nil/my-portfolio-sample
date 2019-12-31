<template>
  <div>
    <main class="contents">
      <nuxt/>
    </main>
  </div>
</template>

<script>
  const Vue = require('vue')
  const VueAnalytics = require('vue-analytics').default

  Vue.use(VueAnalytics, {
    id: 'UA-155171593-1'
  })
</script>