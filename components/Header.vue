<template>
  <div class="navbar navbar-expand-lg na" >
  <a class="navbar-brand" href="#">
    <img src="~~/assets/svg/logo.svg" class="logo"  alt="">
  </a>
  <button class="navbar-toggler" style="color: white !important;" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse menu" id="navbarNavAltMarkup">
    <div class="navbar-nav" style="color:white !important;">
      <h3 class="title">Как это работает?  </h3>
      <h3 class="title">Профессии</h3>
      <h3 class="title">Методология</h3>
      <h3 class="title">Контакты</h3>
    </div>
    <ul>
      <div class="colorpick">
        <li  v-for="color of colors" :key="color">
                  <component style="color:white !important;"
                    :is="`icon-${color}`"
                    :class="getClasses(color)"
                    @click="$colorMode.preference = color"
                  />
        </li>
      </div>
    
     </ul> 
  </div>
</div>

        
    
    
       
    

           
                
          
         
       


</template>

<script>
import IconDark from '@/assets/icons/dark.svg?inline'
import IconLight from '@/assets/icons/light.svg?inline'
import IconAstr from '@/assets/svg/astr.svg?inline'
import IconBackground from '@/assets/svg/background.svg?inline'


export default {
  components: {
    IconDark,
    IconLight,
    IconBackground,
    IconAstr
  },
  data () {
    return {
      colors: ['system', 'light', 'dark']
    }
  },
  methods: {
    getClasses (color) {
      // Does not set classes on ssr preference is system (because we know them on client-side)
      if (this.$colorMode.unknown) {
        return {}
      }
      return {
        preferred: color === this.$colorMode.preference,
        selected: color === this.$colorMode.value
      }
    }
  }
}
</script>

<style>


.perekl{
  
   text-align: center;
    padding: 50px;
}
ul{
  list-style: none;
  padding: 0;
  margin: 0;
}
ul li {
  display: inline-block;
  padding: 5px;
}
 p {
  margin: 0;
  padding-top: 5px;
  padding-bottom: 20px;
}

  .header-bg {
    background-image: url('~assets/svg/background.svg');
    background-repeat:no-repeat;
    background-position: 0 0;
  }

  .nav-link{
    color:white !important;

  }
 

</style>
