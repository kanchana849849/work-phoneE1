<template>
  <v-row justify="center">
    <v-col cols="12" sm="6">
      <v-card color="teal amber ">
        <v-card-title class="">
          <nuxt-link to="/#">
         <v-icon x-large>home</v-icon>
         </nuxt-link>
           <v-spacer></v-spacer>
        <span class="headline dark--text"><h2>Register</h2></span>
          
        </v-card-title>
        
        <v-list>
          <v-list-item @click="">
            <v-list-item-action>
              
            </v-list-item-action>

            <v-list-item-content>
              <v-text-field label="Username"prepend-icon="mdi-account"/>
              <v-text-field label="Password"prepend-icon="mdi-lock"/>
              <v-text-field label="Email"prepend-icon="mdi-email"/>
              <v-text-field label="Tell" prepend-icon="mdi-phone"/>

            </v-list-item-content>
          </v-list-item>

          <v-divider inset></v-divider>

          <v-list-item @click="">
            <v-list-item-action>
            </v-list-item-action>

            <v-list-item-content>
                <center><v-btn class="" tile color="red" prepend-icon="mdi-plus" dark>Add</v-btn></center>
            </v-list-item-content>
          </v-list-item>
        </v-list>
   <center><h5>
     <br>
     </h5></center>
      </v-card>
    </v-col>
  </v-row>
</template>