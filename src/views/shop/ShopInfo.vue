<template>
  <Navbar></Navbar>
  <h4 class="text-center mt-3 mb-5">店家登入驗證資料</h4>

<div class="mt-5">
            <div class="container-fluid border p-2">
    <div class="row justify-content-center">
            <h6 class="col-6">公司名稱</h6>
            <div class="col-6 text-end">貓貓咖啡有限公司</div>
        </div>
</div>

           <div class="container-fluid border p-2">
    <div class="row justify-content-center">
            <h6 class="col-6">登入信箱</h6>
            <div class="col-6 text-end">kay@test.com</div>
        </div>
</div>

           <div class="container-fluid border p-2">
    <div class="row justify-content-center">
            <h6 class="col-6">聯絡電話</h6>
            <div class="col-6 text-end">0900000000</div>
        </div>
</div>


</div>







<Footer class="position-absolute bottom-0 px-5"></Footer>

</template>

<script>
import Navbar from "../../components/CatNavbar.vue";
import Footer from "../../components/HomeFooter.vue";
export default {
  components: {
    Navbar,
    Footer,
  },
};
</script>

<style>

</style>
