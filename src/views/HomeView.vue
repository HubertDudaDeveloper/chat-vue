<template>
  <section class="private-chat">
      <nav class="private-chat__navbar"></nav>
    <div class="private-chat__display">
      <div class="private-chat__display__message">

      </div>
    </div>
    <section class="private-chat__input">
      <input >
      <buttton></buttton>
    </section>
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'HomeView',
  components: {
  }
})
</script>
<style lang="scss">
.private-chat {
  display: grid;
  grid-template-rows: 0.5fr 7fr 0.5fr;
  background-color: white;
  min-height: 90vh;
  border-radius: 35px;
  &__navbar {
    border: 2px orange solid;
  }
  &__display {
    border: 2px burlywood solid;
    &__message {
      border: 2px red solid;
    }
  }
  &__input {
    border: 2px pink solid;
  }
}
</style>
