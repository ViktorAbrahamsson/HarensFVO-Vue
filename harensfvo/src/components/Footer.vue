<template>
  <v-footer class="footer" dark height="auto">
    <v-card class="flex" flat tile>
      <!--<v-card-title class="greenCyan">
        <strong class="subheading footerTitleText">Kontakta oss</strong>
      </v-card-title>-->

      <v-card-text class="footerText">
        <address>
          <p>
            <v-icon class="greenCyan--text" title="Ordförande">gavel</v-icon>Göran Ericsson
          </p>
          <p>
            <v-icon class="greenCyan--text">phone</v-icon>072-249 27 12
          </p>
          <p>
            <v-icon class="greenCyan--text">email</v-icon>
            <a href="mailto:goran@harensten.se">goran@harensten.se</a>
          </p>
        </address>
        <br />
        <address>
          <p>
            <v-icon class="greenCyan--text" title="Utvecklare">developer_mode</v-icon>Viktor
            Abrahamsson
          </p>
          <p>
            <v-icon class="greenCyan--text">email</v-icon>
            <a href="mailto:wicke.abrahamsson@gmail.com">wicke.abrahamsson@gmail.com</a>
          </p>
        </address>
      </v-card-text>

      <v-card-actions class="footerCC justify-center">
        &copy;2023 —
        <strong>HärensFVO</strong>
      </v-card-actions>
    </v-card>
  </v-footer>
</template>

<script>
export default {
  data: () => ({})
};
</script>

<style scoped>

footer {
  border-top: 5px solid #26d07c;
  background: #222;
}

.theme--dark {
  background-color: #222;
}

.footerTitleText {
  margin-left: 50px;
}

.footerText {
  background: #222;
  font-size: 17px;
  display: flex;
  flex-wrap: wrap;
  
  max-width: 1440px;
  margin: 0 auto;
}

.footerText address {
  margin-left: 50px;
}

.footerCC {
  background: #161616;
}

a,
a:hover,
a:visited {
  color: #26d07c;
  text-decoration: none;
}
</style>
