<template>
  <v-card border="false">
    <v-layout>
      <v-img
        src="../static/img/desktop.jpg"
        style="height: 300px; width: 100%"
        cover
      ></v-img>
      <v-navigation-drawer
        location="right"
        class="bg-brown-darken-1"
        style="height: 300px; position: sticky; top: 0"
      >
        <v-list density="compact" nav style="width: 300px">
          <NuxtLink
            to="/"
            class="text-decoration-none text-grey-lighten-5 text-h5"
            ><v-list-item
              prepend-icon="mdi-home-circle"
              title="Home"
              value="home"
            ></v-list-item
          ></NuxtLink>
          <NuxtLink
            to="/about"
            class="text-decoration-none text-grey-lighten-5 text-h5"
            ><v-list-item
              prepend-icon="mdi-human-greeting"
              title="About"
              value="about"
            ></v-list-item
          ></NuxtLink>
          <NuxtLink
            to="/skills"
            class="text-decoration-none text-grey-lighten-5 text-h5"
            ><v-list-item
              prepend-icon="mdi-tools"
              title="Skills"
              value="skills"
            ></v-list-item
          ></NuxtLink>
          <NuxtLink
            to="/portfolio"
            class="text-decoration-none text-grey-lighten-5 text-h5"
            ><v-list-item
              prepend-icon="mdi-file-search-outline"
              title="Portfolio"
              value="portfolio"
            ></v-list-item
          ></NuxtLink>
          <NuxtLink
            to="/notes"
            class="text-decoration-none text-grey-lighten-5 text-h5"
            ><v-list-item
              prepend-icon="mdi-note-multiple-outline"
              title="Notes"
              value="notes"
            ></v-list-item
          ></NuxtLink>
          <NuxtLink
            to="/youtube"
            class="text-decoration-none text-grey-lighten-5 text-h5"
          >
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

  <div>
    <slot />
  </div>
</template>

<script setup></script>

<style scoped></style>
