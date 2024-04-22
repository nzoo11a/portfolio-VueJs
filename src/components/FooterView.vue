<template>
  <v-footer>
      <v-card
        elevation="0"
        rounded="0"
        width="100%"
        class="bg-grey text-center"
      >
<v-card-text>
      <router-link to="https://github.com/nzoo11a">
        <v-btn
          class="mx-4"
          icon
          variant="plain"
          color="white"
        >
          <i class="fas fa-wifi"></i>
        </v-btn>
      </router-link>
    </v-card-text>


        <v-card-text class="text-white">
          <strong>dernière mise a jour le 22/04/2024</strong>
        </v-card-text>
      </v-card>
    </v-footer>
</template>

<script>
export default {

}
</script>

<style>
.v-footer {
  padding: 8px 0 !important;
}
</style>