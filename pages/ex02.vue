<template>
  <div>
    <h1>HELLO {{ first }}age:{{std}} </h1>
    <v-text-field
            v-model="first"
            label="กรุณากรอกชื่อสถาบัน"
            loading
            shaped
          ></v-text-field>
   <v-col cols="12" sm="6" md="4">
          <v-text-field
            label="กรุณากรอกชื่อ-สกุล"
            v-model="first2"
            outlined
            dense
          ></v-text-field>
        </v-col>
    <v-col cols="12" sm="6" md="4">
          <v-text-field
            label="กรุณากรอกสาขาที่เรียน"
            v-model="first3"
            outlined
            dense
          ></v-text-field>
        </v-col>
    <v-col cols="12" sm="6" md="4">
          <v-text-field
            label="กรุณากรอกอายุ"
            v-model="first4"
            outlined
            dense
          ></v-text-field>
        </v-col>
  </div>
</template>
<script>
export default {
  data:function(){
    return{
     name:"alongkorn",
     age:45,
     dep:"information  technology",
     first:"chaiyaphum",
     first2:"กาญจนา พลเสนา",
     first3:"เทคโนโลยีสารสนเทศ",
     first4:"20"
    }
  }
}
</script>