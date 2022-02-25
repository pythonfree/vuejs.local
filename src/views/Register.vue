<template>
  <div class="auth-page">
    <div class="container page">
      <div class="row">
        <div class="col-md-6 offset-md-3 col-xs-12">
          <h1 class="text-xs-center">Sing Up</h1>
          <p class="text-xs-center">
            <router-link to="{name: 'login'}">
              Need an account?
            </router-link>
          </p>
            VALIDATION ERRORS
            <form @submit.prevent="onSubmit">

            </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'McvRegister'
}
</script>