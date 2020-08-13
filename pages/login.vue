<template>
<center>
  <br>
   <v-card width="500" color="teal orange darken-4">
     <v-card-title-center>
      <v-icon size="100" color="yellow accent-3">important_devices</v-icon>
      <h5>ระบุชื่อผู้ใช้และหรัสผ่านก่อนเข้าสู่ระบบ</h5>
     </v-card-title-center>
     <v-card-text>
       <v-form>
         <v-text-field label="Username" 
          prepend-icon="mdi-account-circle"
          />
          <v-text-field 
            :type="showPassword ? 'text' : 'password'" 
            label="Password"
            prepend-icon="mdi-lock"
            :append-icon="showPassword ? 'mdi-eye' : 'mdi-eye-off'"
            @click:append="showPassword = !showPassword"
          />
       </v-form>
     </v-card-text>
     <v-card-actions>
    <nuxt-link to="register"><v-btn class="ma-2" tile color="amber accent-3" dark>REGISTER</v-btn></nuxt-link>
    <v-spacer></v-spacer>
   <v-btn class="ma-2" tile color="amber accent-3" dark @click="doSave">LOGIN</v-btn>
    </v-btn>
    </v-btn>
  </v-card-actions>
   </v-card>
   </center>
</template>
<script>
export default {
  name: "App",
  data() {
    return {
      showPassword: false,
      user: "",
      password: "",
    };
  },
  methods: {
    async doSave() {
      console.log("do save");
      console.log("user:", this.user);
      console.log("password:", this.password);
      //this.$router.push('/register')
      let res = await fetch("http://localhost:7001/list?user=" + this.user);
      let data = await res.json();
    },
  },
};
</script>
