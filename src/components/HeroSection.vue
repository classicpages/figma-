<template>
    <section class="page">
    <div class="welcome">
    <h1><span class="fast">Fast</span> Food Delivery</h1>
   </div>
   <div class="heel">
    <p class="text">Sed ut perspiciatis
         unde omnis iste natus sit voluptatem accusantium doloremque laudantium </p>
    </div>
    
    <div class="us">
        <button class="btn">Order Now</button>
        <a class="watch" href="#">watch video</a>
    </div>
</section>
</template>

<script setup>
</script>


<style scoped>
nav {
    text-align: right;
    word-spacing: 40px;
    margin-top: 0;
    padding-top: 0;
}

.fast {
 font-family: Poppins;
 font-size: 125px;
 font-weight: 700;
 line-height: 118.5px;
 letter-spacing: -0.035em;
 text-align: left;
 color: #FF7E00;

}

.watch {
    margin-left: 20px;

}

.us {
    margin-top: 30px;
    margin-left: 600px;
}

.btn {
    background-color: #2F2F2F;
    width: 130px;
    height: 70px;
    top: 49px;
    left: 93px;
    border-radius: 4px 0px 0px 0px;
    opacity: 0px;
    
}

.welcome {
    text-align: left;
    margin-top: 200px;
    margin-left: 25px;
    width: 820px;
    height: 160px;
    top: 276px;
    left: 297px;
    font-weight: 800;
    font-size: 66px;
    line-height: 80px;
    letter-spacing: -5%;
}

.heel {
    text-align: left;
    margin-top: 80px;

}

</style>