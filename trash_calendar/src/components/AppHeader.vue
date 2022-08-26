<template>
  <div class="d-flex justify-content-between align-items-center shadow p-2 mb-3">
    <h1 class="h4 m-0">{{ title }}</h1>
    <b-icon-three-dots-vertical></b-icon-three-dots-vertical>
  </div>
</template>

<script>
export default {
  data(){
    return {
        title: "ゴミの日",
    }
  }
}
</script>

<style scoped></style>