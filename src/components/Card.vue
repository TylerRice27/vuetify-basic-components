<template>
  <div>
    <h3>Card</h3>
    <!--v-cards-... inside the v-card are nested attributes that you can use  -->
    <v-card
      class="mx-auto"
      color="#26c6da"
      dark
      max-width="400"
    >
      <v-card-title>
        <v-icon
          large
          left
        >
          mdi-twitter
        </v-icon>
        <span class="title font-weight-light">Twitter</span>
      </v-card-title>

      <v-card-text class="headline font-weight-bold">
        "Tom Tom Swayer and A Mean Mean Pride"
      </v-card-text>

      <v-card-actions>
        <v-list-item class="grow">
          <v-list-item-avatar color="red darken-3">
            <v-img
              class="elevation-6"
              src="https://avataaars.io/?avatarStyle=Transparent&topType=ShortHairShortCurly&accessoriesType=Prescription02&hairColor=Black&facialHairType=Blank&clotheType=Hoodie&clotheColor=White&eyeType=Default&eyebrowType=DefaultNatural&mouthType=Default&skinColor=Light"
            ></v-img>
          </v-list-item-avatar>

          <v-list-item-content>
            <v-list-item-title>Evan You</v-list-item-title>
          </v-list-item-content>
          <v-row
          align="center"
          justify="end"
          >
          <v-icon class="mr-1">mdi-heart</v-icon>
          <span class="subheading mr-2">256</span>
          <!-- NOTE v-spacer will fill up as much room as possible until it gets
          to the end of the container and it wont push items outside of it -->
          <!-- <v-spacer></v-spacer> -->
          <span class="mr-1">·</span>
            <v-icon class="mr-1">mdi-share-variant</v-icon>
            <span class="subheading">45</span>
          </v-row>
        </v-list-item>
      </v-card-actions>
    </v-card>
  </div>
</template>
