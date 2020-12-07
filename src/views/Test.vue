<template>
  <div class="about">
    <h1>This is a test page for API calls</h1>
    <label>
      <input v-model="message" />
    </label>
    <button @click="callApi">
      Call API
    </button>
    <router-link to="/">Back to home</router-link>
  </div>
</template>

<script>
  module.exports = {
    data: function () {
      message
    },
    methods: {
      callApi: function () {
        alert("API called with message" + this.data.message + "!");
      }
    }
  }
</script>
