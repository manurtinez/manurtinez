<template>
  <v-sheet color="rgb(32, 32, 32, 0.6)">
    <v-card-title>
      {{ title }}
    </v-card-title>
    <v-row>
      <v-img
        v-for="skill in skills"
        :key="skill.name"
        contain
        :src="skill.src"
        :alt="skill.src"
        max-height="100"
        max-width="100"
      ></v-img>
    </v-row>
  </v-sheet>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      required: true,
    },
    skills: {
      type: Array,
      required: true,
    },
  },
}
</script>

<style></style>
