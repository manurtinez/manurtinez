<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="5">
      <div class="text-center">
        <profile-image />
      </div>
      <v-card>
        <v-card-title class="headline">
          Bienvenid@ a mi pequeño rincón personal de internet
        </v-card-title>
        <v-card-subtitle class="card-subtitle">
          Desarrollador - Estudiante
        </v-card-subtitle>
        <v-card-text>
          <p>
            Soy Manuel, un desarrollador de software de Argentina. Actualmente
            me desempeño como desarrollador web full stack, y me encuentro en el
            4to año de mi carrera de Licenciatura en Sistemas en la UNLP.
          </p>

          <p>
            Cuento con habilidades para <b>desarrollar</b> páginas web y
            sistemas informáticos en varios lenguajes y con un abanico de
            herramientas. Siempre estoy dispuesto a agregar habilidades y
            tecnologías a mi conocimiento actual.
          </p>
        </v-card-text>
      </v-card>
    </v-col>
    <v-col cols="12" sm="8" md="7">
      <skills />
    </v-col>
  </v-row>
</template>

<script>
export default {}
</script>

<style scop Skillsed>
.headline {
  word-break: keep-all;
  text-align: center;
  margin-bottom: 0.5rem;
}
.card-subtitle {
  font-weight: 500;
  font-size: 1.2rem;
  text-align: center;
}
</style>
