<template>
  <section class="hero-section">
    <img class="img" src="/src/assets/17372 [Converted] 1.png" alt="">
    <div class="welcome">
      <h1><span class="fast">Fast</span> <span class="food">Food Delivery</span></h1>
    </div>
    <div class="heel">
      <p>Sed ut perspiciatis unde omnis iste natus sit <br> voluptatem accusantium doloremque laudantium</p>
    </div>
    <div class="actions">
      <button class="btn">Order Now</button>
      <img src="/src/assets/Group 2.png" alt="Arrow Image" class="arrow-img">
      <a class="watch" href="#">Watch Video</a>
    </div>
    <div class="star-rating">
      <img src="/src/assets/emojione_star.png" alt="Star">
      <img src="/src/assets/emojione_star.png" alt="Star">
      <img src="/src/assets/emojione_star.png" alt="Star">
      <img src="/src/assets/emojione_star.png" alt="Star">
      <img src="/src/assets/emojione_star.png" alt="Star">
      <p class="star">5 star rating</p>
      <p class="stars">based on 1788 reviews</p>
    </div>
  </section>
</template>

<script setup>
// No script needed for this component
</script>

<style scoped>
body {
  background-color: wheat;

}

.hero-section {
  text-align:center;
  padding: 20px;
  max-width: 100%;
}

.img {
  width: 100%;
  max-width: 420px;
  height: auto;
  margin-right: 30px;
  float: right;
}


.fast {
  font-family: Poppins;
  font-size: 100px;
  font-weight: 700;
  line-height: 118.5px;
  letter-spacing: -0.035em;
  text-align: left;
  
  color: #FF7E00;
}

.food {
  font-family: Poppins;
  font-size: 52px;
  font-weight: 700;
  line-height: 49.3px;
  text-align: left;
}



.heel {
  font-family: 'Poppins', sans-serif;
  font-size: 1rem;
  font-weight: 400;
  color: #909090;
  margin: 20px 0;
}

.actions {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 20px 0;
}

.actions .arrow-img {
  margin-top: 35px;
}

.btn {
  background-color: #0e0d0d;
  border-radius: 20px;
  padding: 15px 25px;
  color: #fff;
  border: none;
  cursor: pointer;
}

.watch {
  margin-left: 20px;
  color: #000;
  text-decoration: none;
}

.star-rating {
  margin: 20px 0;
}

.star-rating img {
  width: 24px;
  height: 24px;
}

.star {
  font-size: 1rem;
  font-weight: 700;
  color: #000;
  margin-top: 10px;
}

.stars {
  font-size: 1rem;
  font-weight: 300;
  color: #000;
  margin-top: 1
}

/* Media query for screen sizes less than 600px */
@media only screen and (max-width: 600px) {
  .welcome h1 {
    font-size: 1.5rem;
  }

  .fast {
    font-size: 1.5rem;
  }

  .food {
    font-size: 1.2rem;
  }

  .heel {
    font-size: 0.875rem;
    line-height: 1.5;
  }

  .btn {
    padding: 10px 20px;
  }
}
</style>

