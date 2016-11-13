<template>
  
</template>
<script>
import Skeleton from './skeleton/Skeleton.vue'
export default {
components: {
    Skeleton
    
  }
}
</script>
<style lang="stylus" >
/*  Require ET Styles Framework */
@import "et/et";
/*  End of ET Styles Framework */
.intro-header{
background-color: #E1E6EC;
background-image: -webkit-linear-gradient(top, #E1E6EC 2%, #F0F4F7 96%), -webkit-radial-gradient(at 50% 100%, rgba(255, 255, 255, 0.2) 0%, rgba(0, 0, 0, 0.5) 200%);
background-image: linear-gradient(-180deg, #E1E6EC 2%, #F0F4F7 96%), radial-gradient(at 50% 100%, rgba(255, 255, 255, 0.2) 0%, rgba(0, 0, 0, 0.5) 200%);
background-blend-mode: normal, color-burn; }
#awrap{
max-width: 740px;
margin-left: auto;
margin-right: auto;
}
</style>