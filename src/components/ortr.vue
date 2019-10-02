<template>
  <v-container>
    <v-layout text-center wrap>
      <v-flex>
        <v-img src="https://www.orpak.com/wp-content/uploads/OrTR-KB.jpg">
          <div
            @click="click('1')"
            style="position:absolute; top: 52.5%; right: 53.7%; height:4.9%; width: 4.1%; -background-color:black;"
          ></div>
          <div
            @click="click('2')"
            style="position:absolute; top: 52.5%; right: 49.0%; height:4.9%; width: 4.1%; -background-color:black;"
          ></div>
          <div
            @click="click('3')"
            style="position:absolute; top: 52.5%; right: 44.3%; height:4.9%; width: 4.1%; -background-color:black;"
          ></div>
          <div
            style="position:absolute; top: 26.5%; right: 30%; height:10%; width: 39%; color:black;font-size:200%;text-align:left;"
          >{{text}}</div>
        </v-img>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  data: () => ({
    text: "Hello, Press 1-3: "
  }),
  methods: {
    click(x) {
      this.text = this.text + x;
    }
  }
};
</script>
