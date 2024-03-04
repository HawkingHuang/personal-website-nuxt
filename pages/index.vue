<template>
  <v-app>
    <v-main>
      <v-sheet
        class="d-flex align-center justify-center flex-wrap text-center mx-auto my-16 px-4 bg-brown-darken-1"
        elevation="4"
        height="900"
        max-width="1500"
        width="100%"
        rounded
      >
        <div>
          <h2 class="text-h4 font-weight-black text-grey-lighten-5 my-8">
            Hi! The name is Hawking
          </h2>
          <v-img
            src="../static/img/home-profile.jpg"
            style="border-radius: 40%"
          ></v-img>
          <p class="text-h6 font-weight-black text-grey-lighten-5 my-8">
            I'm a programming learner.
          </p>
        </div>
      </v-sheet>
      <v-sheet
        class="d-flex align-center justify-center flex-wrap text-center mx-auto my-16 px-4 bg-grey-lighten-5"
        elevation="4"
        height="900"
        max-width="1500"
        width="100%"
        rounded
      >
        <div>
          <h2 class="text-h4 font-weight-black text-brown-darken-1 my-8">
            I was an intern at Trunk Studio from September to October 2023
          </h2>
          <v-img
            src="../static/img/trunk-studio.jpg"
            style="
              border-radius: 40%;
              width: 50%;
              display: block;
              margin: 0 auto;
            "
          ></v-img>
        </div>
      </v-sheet>
    </v-main>
  </v-app>
</template>

<script></script>

<style scoped></style>
