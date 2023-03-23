<template>
  <div>Lib component</div>
  {{ postalCode }}:{{ address }}
  <!-- <QBtn label="LibBtn"></QBtn> -->
  <!-- <input v-model="address"/>--> 
  
  <button @click="fetchAddress">btn</button> 
  <!-- <QBtn label="qbtn"></QBtn> -->
</template>

<script setup lang="ts">
// import { QBtn } from 'quasar';
import { ref } from 'vue';
// import { Core as YubinBangoCore } from 'yubinbango-core2'

const postalCode=ref('3591145')
const address=ref('')

// 郵便番号から住所を取得する関数
function fetchAddress() {
  // new YubinBangoCore(postalCode.value, function(addr:any) {
  //   // region=都道府県, locality=市区町村, street=町域
  //   const address1 = addr.region + addr.locality + addr.street

  //   address.value = address1
  // })
}
</script>
