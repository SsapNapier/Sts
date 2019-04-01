<template>
      <h1>{{ greeting }}</h1>
</template>

<script>
    module.exports = {
        data: function() {
           return {
               greeting: 'Hello!'
           }
        }
    }
</script>

<style lang="sass?indentedSyntax=true">
    h1
        color:blue
</style>
