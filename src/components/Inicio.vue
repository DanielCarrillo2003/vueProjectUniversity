<template>
    <div>
        <b-container>
            <b-breadcrumb :items="items"></b-breadcrumb>
        </b-container>
        <h1>Inicio Landing</h1>
    </div>
</template>

<script>
 export default {
    data() {
      return {
        items: [
          {
            text: 'Inicio',
            active: true
          }
        ]
      }
    }
  }
</script>

<style>

</style>