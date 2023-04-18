<template>
    <main>
     <div class="text-top">Videos novos toda <b>quinta</b> às <b>20h</b></div>
    
     <a href="https://youtube.com/wdevoficial" target="blank">
        <img alt="Inscreva-se" id="subscribe" src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/subscribe.svg">

     </a>

     <div class="text-bottom">youtube.com/wdevoficial</div>   
    </main>
</template>

<script>
    export default{
        name:'Home'
    }
</script>

<style scoped>

    main{
     background-color: var(--color-background-home); 
     justify-content: center;
     align-items: center;
    }

    .text-top{
        color: var(--color-text-light);
        font-size: 20px;
        margin-bottom: 19px;
    }

    #subscribe{
        width: 240px;
    }
    .text-bottom{
       color:var(--color-text-light);
       font-size: 18px;
       margin-top: 19px;
    }

    @media (min-width:700px){
        #subcribe{
            width: 370px;
        }
    }
</style>