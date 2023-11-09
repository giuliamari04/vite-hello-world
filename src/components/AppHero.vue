<template>
    <header>
        <div class="container pt-5">
  <div class="jumbotron">
    <h1>{{ title }}</h1>      
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero voluptatum a enim at. Corporis tempora impedit quaerat sequi alias! Sint porro veritatis repellat earum labore minus aut? Numquam, dolorum. Aliquam!</p>
  </div>
</div>      
      
   
    </header>
</template>

<script>
    export default{
        name:'AppHero',
        componets:{

        },
        data(){
            return{
                title:'Titolone Hero',
            }
        },
        methods:{
            
        }
    }
</script>



<style lang="css" scoped>
    header{
       background-image: url(../assets/img/jonatan-pie-3l3RwQdHRHg-unsplash.jpg);
       background-size:100%;
       background-repeat: no-repeat;
       background-position:top ;
       color: white;
       height: 40vh;
    }
</style>
