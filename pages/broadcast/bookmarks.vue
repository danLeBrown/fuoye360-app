<template>
  <div>
    <div class="div-title">
      <div class="title-container">
        <h3 class=""><i class="fas fa-bookmark"></i> Bookmarks</h3>
      </div>
    </div>
    <br /><br />
    <div>
      <BroadcastGridComponent />
    </div>
  </div>
</template>

<script>
import BroadcastGridComponent from '~/components/broadcast/BroadcastGridComponent.vue'
export default {
  name: 'Bookmarks',
  components: { BroadcastGridComponent },
}
</script>

<style scoped></style>
