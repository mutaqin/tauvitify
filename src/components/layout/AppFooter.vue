<template>
  <v-footer app>
    <div class="text-caption pt-6 pb-1 pt-md-0 text-center text-no-wrap">
      &copy; Copyright 2024
          <a
            href="https://github.com/mutaqin"
            class="font-weight-bold text-primary"
            target="_blank"
            >Muttaqin Alanshoriy</a
          >
    </div>
    <v-spacer />
    <v-defaults-provider
      :defaults="{ VBtn: { variant: 'text', size: 'x-small' } }"
    >
      <AppNotification />
      <ButtonSettings />
    </v-defaults-provider>
  </v-footer>
</template>
<style>
.v-footer {
  padding: 0px 10px !important;
  > .v-btn--icon {
    .v-icon {
      height: 1.25em;
      width: 1.25em;
    }
  }
}
</style>
