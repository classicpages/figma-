<template>
    <section class="page">
        <img class="img" src="/src/assets/17372 [Converted] 1.png" alt="">
    <div class="welcome">
    <h1><span class="fast">Fast</span> <span class="food">Food Delivery</span></h1>
   </div>
   <div class="heel">
    <p>Sed ut perspiciatis
         unde omnis iste natus sit <br> voluptatem accusantium doloremque laudantium </p>
    </div>
    
    <div>
        <button class="btn">Order Now</button>
        <a class="watch" href="#">watch video</a>
    </div>

    <div class="star">
        <img src="/src/assets/emojione_star.png">
        <img src="/src/assets/emojione_star.png">
        <img src="/src/assets/emojione_star.png">
        <img src="/src/assets/emojione_star.png">
        <img src="/src/assets/emojione_star.png">
    </div>
    <p class="star">5 star rating </p>
    <p class="stars">based on 1788 reviews</p>

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

.star {
    color: black;
    font-size: 17px;
    font-weight: 500;
}

.stars {
 font-size: 17px;
 font-weight: 300;
 color: #000;
}

.fast {
 font-family: Poppins;
 font-size: 120px;
 font-weight: 700;
 line-height: 118.5px;
 letter-spacing: -0.035em;
 text-align: left;
 color: #FF7E00;
}

.food {
    color: #000;
    font-family: Poppins;
font-size: 52px;
font-weight: 700;
line-height: 49.3px;
text-align: left;

}


.watch {
    margin-left: 20px;
    color:#000;
}

.us {
    margin-top: 30px;

}
.btn {
    background-color:#0e0d0d;
    border-radius: 20px;
    padding-top: 15px;
    padding-bottom: 15px;
    padding-left: 25px;
    padding-right: 25px;
    color: #fff;
}

.welcome {
    text-align: left;
    margin-top: 80px;
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
    margin-top: 60px;
    font-family: Poppins;
    font-size: 19px;
    font-weight: 400;
    line-height: 30.54px;
    text-align: left;
    color:#909090;
}


.img {
    width: 440px;
    height: 400px;
    top: 1219;
    float: right;
  }

  .page {
    background-color: #fff;
}


</style>