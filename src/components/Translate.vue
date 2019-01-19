<template>
  <div class="translate">
      <h1>{{ msg }}</h1>
      <vue-speech @onTranscriptionEnd="onEnd"/>
    <button v-on:click="OnEnd()">Click me</button>
  </div>
</template>

<script>
import Vue from 'vue';
import VueSpeech from 'vue-speech';
Vue.use(VueSpeech);

export default {
  name: 'Translate',
  props: {
    msg: String
  },
  methods: {
    onEnd({ lastSentence, transcription}){
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
