<template>
  <v-footer color="primary" absolute padless>
    <v-row>
      <v-col order="first">
        <v-card flat>
          <v-card-text class="justify-center">
            <v-icon x-large @click="$emit()">mdi-home</v-icon>
          </v-card-text>
        </v-card>
      </v-col>
      
    </v-row>
  </v-footer>
</template>

<script>
export default {
  name: "Footer",
}
</script>