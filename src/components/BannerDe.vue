<script setup>

</script>

<template>
  <v-sheet
      class="d-flex align-center justify-center flex-wrap text-center px-4 "
      width="100%"
  >
    <v-row>
      <v-col cols="12" style="z-index: 1">
        <v-row >
          <v-col cols="4">
            <v-img src="https://i.ebayimg.com/images/g/GYcAAOSwoWdlMMxG/s-l1200.webp" width="max-width"></v-img>
          </v-col>
          <v-col cols="4">
            <v-img src="https://i.ebayimg.com/images/g/GYcAAOSwoWdlMMxG/s-l1200.webp" width="max-width"></v-img>
          </v-col>
          <v-col cols="4">
            <v-img src="https://i.ebayimg.com/images/g/GYcAAOSwoWdlMMxG/s-l1200.webp" width="max-width"></v-img>
          </v-col>
        </v-row>
      </v-col>
      <v-col cols="12" style="z-index: 2" class="mt-n16">
        <v-row class="text-black mt-n16">
          <v-spacer></v-spacer>
          <v-col cols="10" style="border: 10px solid #3b3b3b;border-radius: 30px;background-color: #d3d3d3">
            <v-row>
              <v-col cols="4" class="pa-0" style="border-right: 2px solid #3b3b3b">
                <v-text-field label="Origen" style="color: black" hide-details></v-text-field>
              </v-col>
              <v-col cols="4" class="pa-0" style="border-right: 2px solid #3b3b3b">
                <v-text-field label="Destino" hide-details></v-text-field>
              </v-col>
              <v-col cols="2" class="pa-0">
                <input type="date" name="" id="" style="margin-top: 15px">
              </v-col>
              <v-col cols="2" class="pa-0">
                <v-btn color="blue" width="101%" height="100%" style="border-radius: 19px">BUSCAR</v-btn>
              </v-col>
            </v-row>
          </v-col>
          <v-spacer></v-spacer>
        </v-row>
      </v-col>
    </v-row>
  </v-sheet>
</template>

<style scoped>
.v-text-field__details {
  background: gainsboro;
}
</style>