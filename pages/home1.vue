<template>
  <v-card
    :loading="loading"
    class="mx-auto my-12"
    max-width="374"
  >
<center><img src="../image/pro.png" height="450"></center>
    <v-card-title>Kanchana Phonsena</v-card-title>

    <v-card-text>
      <v-row
        align="center"
        class="mx-0"
      >
        <v-rating
          :value="4.5"
          color="amber"
          dense
          half-increments
          readonly
          size="14"
        ></v-rating>

        <div class="grey--text ml-4"> นางสาวกาญจนา พลเสนา</div>
      </v-row>

      <div class="my-4 subtitle-1">
        กำลังศึกษาที่วิทยาลัยเทคนิคชัยภูมิ
      </div>

      <div>ศึกษาอยู่ระดับประกาศนียบัตรวิชาชีพชั้นสูงชั้นปีที่ 2 แผนกเทคโนโลยีสารสนเทศ เกิดเมื่อ 4 กุมภาพันธ์ พุทศักราช 2543</div>
    </v-card-text>

    <v-divider class="mx-4"></v-divider>


    <v-card-actions>
      <v-btn
        color="deep-purple lighten-2"
        text
        @click="reserve"
      >
        backe home
      </v-btn>
    </v-card-actions>
  </v-card>
</template>
<script>
export default {
    layout:'defaulthome',
}
</script>
