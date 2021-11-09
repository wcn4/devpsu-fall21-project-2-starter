<template>
  <v-footer
    padless
    absolute
  >
    <v-card
      flat
      tile
      class="text-center title-center"
      style="width:100%;"
    >
      <v-card-subtitle>
        Adapted from <a href="https://github.com/Vedanta6/flask_vue">Vedanta6's Vue Flask Project</a> for <a href="https://github.com/wcn4/devpsu-fall21-project-2-starter">DevPSU</a>
      </v-card-subtitle>
      <v-card-text class="text-muted">
        <p>{{ new Date().getFullYear() }} <span>&copy; All rights reserved</span></p>
      </v-card-text>
    </v-card>
  </v-footer>
</template>
