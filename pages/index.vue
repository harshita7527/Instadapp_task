<template>
  <div>
    <MainContent />
  </div>
</template>

<script>
import MainContent from "../components/MainContent.vue"

export default {
  name: 'IndexPage',
  components: {
      MainContent
  },
  head() {
        return {
            title: 'Instadapp task',
            meta: [
                {
                    hid: 'description',
                    name: 'description',
                    content: 'test frontend page'
                }
            ]
        }
    }
}
</script>
