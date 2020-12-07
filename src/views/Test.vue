<template>
  <div class="about">
    <h1>This is a test page for API calls</h1>
  </div>
  <button @click="callApi">
    Call API
  </button>
</template>

<script>
  function callApi() {
    alert("API called!")
  }
</script>
