<template>
  <v-row justify="center">
    <v-col cols="12" sm="8">
      <v-card color="teal darken-4">
        <v-card-title class="white">
         <v-img src="https://bestreview.asia/wp-content/uploads/2020/04/Desktop-PC.jpg" height="300px"></v-img>
          
        </v-card-title>
        <center><span class="headline dark--text">Register</span></center>
        <v-list>
          <v-list-item @click="">
            <v-list-item-action>
              
            </v-list-item-action>

            <v-list-item-content>
              <v-text-field label="Username"prepend-icon="mdi-account"/>
              <v-text-field label="Password"prepend-icon="mdi-lock"/>
              <v-text-field label="Email"prepend-icon="mdi-email"/>
              <v-text-field  label="Tell" prepend-icon="mdi-phone"/>
            </v-list-item-content>
          </v-list-item>

          <v-divider inset></v-divider>

          <v-list-item @click="">
            <v-list-item-action>
            </v-list-item-action>

            <v-list-item-content>
               <center><h6>กรุณาเพิ่มข้อมูลให้ครบทุกช่อง</h6></center>
            </v-list-item-content>
          </v-list-item>
        </v-list>

       
      </v-card>
    </v-col>
  </v-row>
</template>