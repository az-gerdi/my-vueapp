<template>
  <div class="home">
    <KEditor />
  </div>
</template>

<script>
// @ is an alias to /src
import KEditor from "@/components/KEditor.vue"

export default {
  name: "home",
  components: {
    KEditor
  }
}
</script>
