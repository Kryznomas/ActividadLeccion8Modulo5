<template>
  <q-header elevated>
    <q-toolbar>
      <q-toolbar-title>
        Prueba con Quasar
      </q-toolbar-title>
      <q-btn color="primary" glossy label="Home" href="#index" />
      <q-btn color="standard" stretch flat label="Articulos" href="#articles" />
      <q-btn color="standard" stretch flat label="Contacto" href="#footer" />
    </q-toolbar>
  </q-header>
</template>
<script>
export default {
  name: "Navbar"
};
</script>