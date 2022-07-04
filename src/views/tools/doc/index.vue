<template>
  <elFrame :src="docApi" />
</template>
<script>
import { mapGetters } from 'vuex'
import elFrame from '@/components/Iframe/index'
export default {
  name: 'Doc',
  components: { elFrame },
  computed: {
    ...mapGetters([
      'docApi'
    ])
  }
}
</script>
