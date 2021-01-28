<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated>
      <q-toolbar class="bg-white text-blue container">
        
        <q-toolbar-title>
          <q-btn @click="$router.push('/') " >
            <img src="../assets/logo.png" class="logo" />
          </q-btn>
        </q-toolbar-title>
      </q-toolbar>
    </q-header>
    <q-footer elevated>
        <q-toolbar class="bg-white text-blue container">
          <q-toolbar-title class="Endereço">Address: Q SRTV/SUL QUADRA 701 CONJUNTO L LOTE 38 <br/> CNPJ:37.311.173/0001-30 </q-toolbar-title>
        </q-toolbar>
      </q-footer>
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
</script>

<style>
a{
  text-decoration: none;
}
.logo{
  height: 40px;
}
.Endereço{
  text-align: center;
  font-size: 15px;
}
</style>