<template>
<q-layout>
    <q-page-container>
      <q-page class="flex items-center justify-center">
        <q-card flat bordered class="login-card">
          <q-card-section class="q-gutter-md column">
            <q-input placeholder="Username" />
            <q-input  placeholder="Password" />
            <q-btn outline color="primary">Login</q-btn>
          </q-card-section>
        </q-card>
      </q-page>
    </q-page-container>
  </q-layout>
</template>

<script>
</script>

<style>
.login-card {
  max-width: 400px;
  width: 95vw;
}
</style>
