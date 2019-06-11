// .vuepress/theme/Layout.vue
<template>
  <Layout>
    <footer slot="page-bottom">
      Please read through this site's <a href="/disclaimers.html">disclaimers</a> before using this site. If you have questions or concerns about this site's content, please <a href="/contact.html">contact</a> me.
    </footer>
  </Layout>
</template>

<script>
import Layout from '@default-theme/Layout.vue'
export default {
  components: {
    Layout,
  }
}
</script>
