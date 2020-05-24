<template>
  <v-app>
    <center>
   <div class="my-2">
   <v-btn color="primary" exact to="/login">Login</v-btn>
   <br>
   <br>
   <br>
   <v-btn color="primary" exact to="/formulario">Registro</v-btn>
   </div>
    </center>
<router-view >
</router-view>
  </v-app>
     

</template>

<script>

import login from '@/views/login'
import formulario from '@/views/formulario'

export default {
  name: 'App',

  components: {
   
    login,
    formulario,
  },

  data: () => ({
    //
  }),
};
</script>
