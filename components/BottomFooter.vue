<template>
  <v-footer height="auto" :fixed="false" dark>
    <v-card flat tile class="lighten-1 white--text text-xs-center" width="100%">
      <v-card-text class="light-blue darken-4">
        <!-- <v-btn
          v-for="icon in icons"
          :key="icon.ico"
          icon
          class="mx-3 white-text"
          :href="icon.link"
          :target="'_blank'"
          rel="noopener"
        >
          <v-icon size="24px">{{ icon.ico }}</v-icon>
        </v-btn> -->
        <v-flex xs12 text-xs-center :to="'https://github.com/ceit94'">
          <a
            href="https://github.com/ceit94"
            target="_blank"
            rel="noopener"
            class="yellow--text text--accent-2 caption"
            style="text-decoration: none"
          >{{footer}}</a>
        </v-flex>
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<script>
export default {
  name: 'BottomFooter',
  data: () => ({
    icons: [
      { ico: 'mdi-github-circle', link: 'https://github.com/ceit94' },
      { ico: 'mdi-telegram', link: 'https://t.me/ceit94' },
      { ico: 'alternate_email', link: 'mailto:grad@ceit94.ir' }
    ],
    footer:
      'دانشجویان ورودی سال ١٣٩٤ دانشکده مهندسی کامپیوتر و فناوری اطلاعات دانشگاه صنعتی امیرکبیر - grad@ceit94.ir'
  })
};
</script>

<style scoped>
</style>
