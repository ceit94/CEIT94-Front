<template>
  <v-content>
    <v-container>
      <v-layout row wrap align-center justify-center class="mb-3">
        <v-flex xs11 class="text-xs-center">
          <h1 class="iranblack blue--text text--darken-3">جامعه دانش‌آموختگان ورودی سال ١٣٩٤</h1>
          <h2 class="iranblack">دانشکده مهندسی کامپیوتر و فناوری اطلاعات</h2>
          <h3 class="iranblack">دانشگاه صنعتی امیرکبیر (پلی‌تکنیک تهران)</h3>
          <br>
          <hr>
          <br>
          <h1
            class="iranblack blue--text text--darken-3"
            style="color: red"
          >سایت در حال آماده سازی اولیه میباشد - لطفا منتظر بمانید</h1>
        </v-flex>
      </v-layout>
      <!-- <countdown date="June 23, 2018" :button="button"></countdown>
      <v-layout row wrap align-center justify-center>
        <v-flex xs6 sm4 md3 lg2 v-for="(item, index) in studentsArray" :key="index">
          <div class="text-xs-center no-underline">
            <nuxt-link :to="'/' + item.username">
              <v-avatar size="80%">
                <img
                  class="elevation-7 mb-1"
                  width="100%"
                  :src="$helper.avatar(item)">
              </v-avatar>
              <h3 class="iranblack light-blue--text text--darken-3">{{$persianJS.userName(item)}}</h3>
              <p class="iranblack caption text-xs-center grey--text pt-1 pb-3">{{$persianJS.englishNumber(item.std_numbers)}}</p>
            </nuxt-link>
          </div>
        </v-flex> 
      </v-layout>-->
    </v-container>
  </v-content>
</template>

<script>
// import Countdown from "../components/Profile/Countdown";
// export default {
//   name: "index",
//   components: {Countdown},
//   auth: false
// }
</script>

<style>
.no-underline > a {
  text-decoration: none;
}
</style>
