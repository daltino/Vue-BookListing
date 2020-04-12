<template>
  <div><h1>{{title}}</h1></div>
</template>

<script>
export default {
  name: 'BookList',
  data: function() {
    return {
      title: 'All Books',
    }
  }
}
</script>

<style lang="scss">
  h1, h2 {
    font-weight: normal;
  }
</style>
