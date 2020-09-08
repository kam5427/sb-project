<template>

     <div class="container-fluid header-bg">
       <div class="row" style="padding-top:30px; height: 210px;">
         <div class="col-3" style="margin-left: 120px;">
           <img src="~~/assets/svg/logo.svg" alt="">
         </div>
         <div class="col-7 gy-5 ml-3">
           <ul class="nav">
             <li class="nav-item">
               <a class="nav-link active disabled" aria-current="page" href="#"><h4>Как это работает?</h4></a>
             </li>
             <li class="nav-item">
               <a class="nav-link disabled" href="#"><h4>Профессии</h4></a>
             </li>
             <li class="nav-item">
               <a class="nav-link disabled" href="#"><h4>Методология</h4></a>
             </li>
             <li class="nav-item">
               <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true"><h4>Контакты</h4></a>
             </li>
           </ul>
         </div>
       </div>
     </div>

</template>

<script>
export default {

}
</script>

<style>
  .header-bg {
    background-image: url('~assets/svg/background.svg');
    background-repeat:no-repeat;
    background-position: 0 0;
  }

  .nav-link{
    color:white !important;

  }
</style>
