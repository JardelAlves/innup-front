<template>
  <v-footer color="primary" absolute padless>
    <v-card width="100%" >
      <v-container fluid>
        <v-row align-content="center" justify="center">
          <v-col align-self="center">
            <v-btn icon>
              <v-icon large>mdi-home</v-icon>
            </v-btn>
          </v-col>

          <v-col align-self="center">
            <v-btn icon>
              <v-icon large>mdi-magnify</v-icon>
            </v-btn>
          </v-col>

          <v-col align-self="center">
            <v-btn icon>
              <v-icon large>mdi-account</v-icon>
            </v-btn>
          </v-col>

        </v-row>
      </v-container>
    </v-card>
  </v-footer>
</template>

<script>
export default {
  name: "Footer",
}
</script>