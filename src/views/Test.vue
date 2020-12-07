<template>
  <div class="about">
    <h1>This is a test page for API calls</h1>
    <button @click="callApi">
      Call API
    </button>
    <router-link to="/">Back to home</router-link>
  </div>
</template>

<script>
  function callApi() {
    alert("API called!")
  }
</script>
