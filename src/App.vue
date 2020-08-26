<template>
  <v-app>
    <v-app-bar
      app
      color="#FFFFFF"
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="https://www.capgemini.com/br-pt/wp-content/themes/capgemini-komposite/assets/images/logo.svg"
          transition="scale-transition"
          width="150"
        />
       
      </div>
    </v-app-bar>

    <v-main>
      <Login/>
    </v-main>
  </v-app>
</template>

<script>
import Login from './components/Login';

export default {
  name: 'App',

  components: {
    Login,
  },

  data: () => ({
    //
  }),
};
</script>
<style>
  #login-desafio .v-main{
    display: block;
  }
  .button-login{
    width: 100%;
    color: #FFFFFF !important;
    border-radius: 3px;    
  }
</style>