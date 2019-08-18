<template>
  <Layout>
    <footer slot="page-bottom">
      <!-- Creative Commons License Logo -->
      <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">
        <img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" />
      </a>
      <br/>
      This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
      <br/>
      <!-- Disclaimers and contact -->
      Please read through this site's <a href="/disclaimers.html">disclaimers</a> before using this site.
      <br/>
      If you have questions or concerns about this site's content, please <a href="/contact.html">contact</a> me.
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
