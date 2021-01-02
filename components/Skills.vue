<template>
  <v-container class="skills-container">
    <v-row class="row" justify="center" align="center">
      <span class="text-sm-h3">Mis skills</span>
    </v-row>
    <v-row class="row" justify="center" align="center">
      <SkillsCard
        v-for="category in categories"
        :key="category.title"
        :title="category.title"
        :skills="category.skills"
      />
    </v-row>
  </v-container>
</template>

<script>
export default {
  data() {
    return {
      categories: [
        {
          title: 'Frontend',
          skills: [
            {
              name: 'React',
              src: '/logos/react.png',
              alt: 'logo de react',
            },
            {
              name: 'VueJS',
              src: '/logos/vue.png',
              alt: 'logo de vue',
            },
          ],
        },
      ],
    }
  },
}
</script>

<style scoped>
.skills-container {
  height: 100%;
}
.row {
  margin-bottom: 1rem;
}
</style>
