<template>
   <v-card>
     <v-card-title>
       <h1>Login</h1>
     </v-card-title>
     <v-card-text>
       <v-form>
         <v-text-field label="Username" 
          prepend-icon="mdi-account-circle"
         />
         <v-text-field label="Password" prepend-icon="lock" append-icon="visibility_off"/>
       </v-form>
     </v-card-text>
     <v-card-actions>
    <nuxt-link to="register"><v-btn class="ma-2" tile color="green" dark>REGISTER</v-btn></nuxt-link>
    <v-spacer></v-spacer>
   <v-btn class="ma-2" tile color="blue" dark>LOGIN</v-btn>
    </v-btn>
    </v-btn>
  </v-card-actions>
   </v-card>
</template>