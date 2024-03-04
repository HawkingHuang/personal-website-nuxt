<template>
  <v-card>
    <v-layout>
      <v-navigation-drawer location="right" permanent>
        <v-list density="compact" nav>
          <NuxtLink to="/"
            ><v-list-item
              prepend-icon="mdi-home-circle"
              title="Home"
              value="home"
            ></v-list-item
          ></NuxtLink>
          <NuxtLink to="/about"
            ><v-list-item
              prepend-icon="mdi-human-greeting"
              title="About"
              value="about"
            ></v-list-item
          ></NuxtLink>
          <NuxtLink to="/skills"
            ><v-list-item
              prepend-icon="mdi-tools"
              title="Skills"
              value="skills"
            ></v-list-item
          ></NuxtLink>
          <NuxtLink to="/portfolio"
            ><v-list-item
              prepend-icon="mdi-file-search-outline"
              title="Portfolio"
              value="portfolio"
            ></v-list-item
          ></NuxtLink>
          <NuxtLink to="/notes"
            ><v-list-item
              prepend-icon="mdi-note-multiple-outline"
              title="Notes"
              value="notes"
            ></v-list-item
          ></NuxtLink>
          <NuxtLink to="/youtube">
            <v-list-item
              prepend-icon="mdi-youtube"
              title="YouTube"
              value="youtube"
            ></v-list-item
          ></NuxtLink>
        </v-list>
      </v-navigation-drawer>
      <v-main style="height: 300px"></v-main>
    </v-layout>
  </v-card>
</template>

<script setup></script>

<style scoped></style>
