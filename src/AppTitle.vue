<template>

  <AppHero />

  <main class="d-flex  justify-content-center">
    <h1 class=" mt-5">{{ title }}</h1>
  </main>

</template>

<script>
import AppHero from './components/AppHero.vue'

    export default{
        name:'AppTitle',
        components:{
          AppHero,
        },
        data(){
            return{
                title:'La mia prima app con Vite!'
            }
        },
        methods:{
            
        }
    }
</script>



<style lang="css" scoped>
main{
  text-align: center;
  height: 60vh;
  border-top: 10px solid black;
  background: rgb(23,97,131);
  background: linear-gradient(90deg, rgba(23,97,131,1) 9%, rgba(41,166,168,1) 17%, rgba(32,131,85,1) 35%, rgba(32,123,162,1) 58%, rgba(37,170,98,1) 68%, rgba(19,85,117,1) 81%, rgba(11,89,123,1) 94%, rgba(5,38,71,1) 100%);
}
h1{
  width: 50%;
  padding: 10px;
  height:fit-content;
  border-radius: 20px;
  background-color: rgba(255, 255, 255, 0.61);
  animation: mymove 5s infinite;
}
h1:hover{
  transform: scale(1.2);
}


@keyframes mymove {
  0% {transform: scale(1);}
  50% {transform: scale(1.2);}
  100% {transform: scale(1);}
}
</style>

