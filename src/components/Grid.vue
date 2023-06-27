<template>
  <div>
    <h3>Grid</h3>
    <v-card class="mt-5 mb-8">
      <v-card-text>
        <!-- v-container accepts props -->
        <v-container>
          <!-- no-gutters take away space -->
          <!-- dense will make the space around your cols and rows smaller -->
          <v-row>
            <!-- cols for the amount of columns -->
            <!-- Can do offset as well -->
            <!-- NOTE col-6 at md and up -->
            <v-col cols="12" md="6">
              <v-card
                class="pa-2"
                outlined
                tile
              >
                Column
              </v-card>
            </v-col>
          </v-row>
          <!-- NOTE justify content like this/ Look into align items syntax -->
          <v-row justify="space-between">
            <v-col cols="4">
              <v-card
                class="pa-2"
                outlined
                tile
              >
                Column
              </v-card>
            </v-col>
            <v-col cols="4">
              <v-card
                class="pa-2"
                outlined
                tile
              >
                Column
              </v-card>
            </v-col>
          </v-row>
        </v-container>
      </v-card-text>
    </v-card>
  </div>
</template>
