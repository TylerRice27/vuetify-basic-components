<template>
  <div>
    <h3>Buttons</h3>
    <v-card class="mt-5 mb-8">
      <v-card-text>
        <v-row>
          <v-col cols="12">
            <!-- v-ripple gives a cool ripple effect on click -->
            <button  v-ripple class="elevation-2 py-2 px-4">
              Custom Button
            </button>
          </v-col>
          <v-col cols="12">
              <v-btn small>Small button</v-btn>
            </v-col>
               <v-col cols="12">
                <v-btn large>Large button</v-btn>
              </v-col>
                 <v-col cols="12">
                <v-btn large text>Text Button/Hover over me</v-btn>
              </v-col>
                 <v-col cols="12">
                <v-btn large outlined >Large Outlined Button</v-btn>
              </v-col>
                 <v-col cols="12">
                <v-btn rounded depressed>Rounded/Depressed/No Eval</v-btn>
              </v-col>
          <v-col cols="12">
            <v-btn block>Block</v-btn>
          </v-col>
          <v-col cols="12">
            <!-- You can wrap a button around an Icon -->
            <v-btn>
              <v-icon>mdi-pencil</v-icon>
            </v-btn>
            </v-col>
            <v-col cols="12">
              <v-btn class="red white--text">Red/White</v-btn>
            </v-col>
            <v-col cols="12">
                <v-btn>Normal</v-btn>
              </v-col>
        </v-row>
        <v-row>
          <v-col cols="12">
            <v-btn tile outlined color="success">
              <v-icon left>mdi-pencil</v-icon> Edit
            </v-btn>
          </v-col>
        </v-row>
        <v-row>
          <v-col cols="12">
            <v-btn text icon color="pink">
              <v-icon>mdi-heart</v-icon>
            </v-btn>
            <v-btn text icon color="deep-orange">
              <v-icon>mdi-thumb-up</v-icon>
            </v-btn>
          </v-col>
        </v-row>
        <v-row>
          <v-col>
            <v-btn class="mx-2" fab dark color="indigo">
              <v-icon dark>mdi-plus</v-icon>
            </v-btn>
          </v-col>
        </v-row>
      </v-card-text>
    </v-card>
  </div>
</template>
