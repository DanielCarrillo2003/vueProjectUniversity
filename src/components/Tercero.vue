<template>
   <div>
        <b-container>
            <b-breadcrumb :items="items"></b-breadcrumb>
        </b-container>
        <h1>Información</h1>
    </div>
</template>

<script>
export default {
    data() {
      return {
        items: [
          {
            text: 'Inicio',
            to: { name: 'inicio' }

          },
          {
            text: 'Renta',
            to: { name: 'main' }

          },
          {
            text: 'Información',
            active: true
          }
        ]
      }
    }
  }
</script>

<style>

</style>