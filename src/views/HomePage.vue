<script setup>

function Logout() {
  localStorage.removeItem('token');
}

</script>

<template>
  <p class="display-3">
    Home Page
  </p>

  <button
    class="btn btn-lg btn-primary"
    @click="Logout"
  >
    Log out
  </button>
</template>