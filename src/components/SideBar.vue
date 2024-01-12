<template>
  <div>
    <b-sidebar
      id="sidebar-1"
      title="Sidebar"
      shadow
      visible="true"
      bg-variant="dark"
      text-variant="light"
      no-header
      width="200px"
      no-close-on-route-change="true"

    >
      <div class="px-3 py-2" id="sidebarContent">
        <div>
          <b-button-group vertical id="buttons">
            <b-button>
              <b-link :to="{ name: 'inicio' }">Inicio
              </b-link>
            </b-button>
            <b-button>
              <b-link :to="{ name: 'main' }">Renta</b-link>
            </b-button>
            <b-button>
              <b-link :to="{ name: 'tercero' }">Información</b-link>
            </b-button>
           <b-button>
              <b-link :to="{ name: 'ofertar' }">Ofertar
              </b-link>
            </b-button>
            <b-button>
              <b-link :to="{ name: 'ofertar' }">Ofertar
              </b-link>
            </b-button>
            <b-button>
              <b-link :to="{ name: 'ofertar' }">Ofertar
              </b-link>
            </b-button>
            <b-button>
              <b-link :to="{ name: 'ofertar' }">Ofertar
              </b-link>
            </b-button>
            <b-button>
              <b-link :to="{ name: 'ofertar' }">Ofertar
              </b-link>
            </b-button>
          </b-button-group>
        </div>
      </div>
    </b-sidebar>
  </div>
</template>

<style scoped>
#sidebarContent {
  margin-top: 56px;
}

#buttons {
  width: 100%;
}

#buttons a{
  color: white;
  text-decoration: none;
  padding: 5px 30px
}
</style>
