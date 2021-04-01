<template>
  <q-layout view="hHh lpR fFf">


    <q-header reveal elevated class="bg-primary text-white">
      <q-toolbar>
        <q-toolbar-title>
          <q-avatar>
            <img src="https://cdn.quasar.dev/logo/svg/quasar-logo.svg">
          </q-avatar>
          Dakik
        </q-toolbar-title>
      </q-toolbar>
    </q-header>
    
    <q-footer elevated class="bg-primary text-white" height-hint="98">

      <q-tabs align="left">
        <q-route-tab to="/home" label="Kalan Sürem" icon="home" />
        <q-route-tab to="/hes" label="Hes Kodlarım" icon="home" />
        <q-route-tab to="/gecmis" label="Geçmiş" icon="home" />
      </q-tabs>
    </q-footer>

    <q-page-container>
      <router-view />
    </q-page-container>

  </q-layout>
</template>

<script>
export default {
  data () {
    return {
    }
  }
}
</script>
