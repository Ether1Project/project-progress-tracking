<template>
<div class="main-container">

  <router-view></router-view>

  <HeaderStartup />

  <HeroStartup />

  

  <div id="ethoblack"> </div>
  <EthoBlackProgress1 />

  <FooterMain FooterStyle="bg_drak-footer" />

</div>
</template>

<script>
import HeaderStartup from '../components/HeaderStartup'

import FooterMain from '../components/FooterMain'
import EthoBlackProgress1 from '@/components/EthoBlackProgress1.vue'

export default {
  name: 'app',
  components: {
    HeaderStartup,
    
    FooterMain,
    EthoBlackProgress1,
  }
}
</script>
