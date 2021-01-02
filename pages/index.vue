<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <div class="text-center">
        <profile-image />
      </div>
      <v-card>
        <v-card-title class="headline">
          Bienvenid@ a mi pequeño rincón personal de internet
        </v-card-title>
        <v-card-text>
          <p>
            Soy Manuel, un desarrollador de software de Argentina. Actualmente
            me desempeño como desarrollador web full stack, y me encuentro en el
            4to año de mi carrera de Ingenieria de Software en la UNLP.
          </p>
        </v-card-text>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {}
</script>

<style scoped>
.headline {
  word-break: keep-all;
  text-align: center;
}
</style>
