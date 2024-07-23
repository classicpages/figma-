<template>
    <section>
        <nav >
            <p class="site"><img src="/src/assets/chef-hat (2) 1.png"> Foo</p>
                <div class="navbar">
                  <div class="navbars">Home</div>
                  <div class="navbar">Menu</div>
                  <div class="navbar">Contact</div>
                  <div class="navbar">Shop</div>
    
                  <div class="search-container">
                    <input type="text" placeholder="Search...">
                </div>
                </div>
                <HeroSection />
        </nav>   
    </section>
       
</template>
<script setup>

</script>
<style scoped>

.navbar {
width: 80px;
height: 58px;
text-align: right;
display: flex;
margin-top: 20px;
color: #fff;
margin-left: 15px;
font-weight: 400;
font-size: 14px;
}

.search-container {
    margin-top: 20px;
    margin-left: 20px;
}

.navbars {
margin-left: 250px;
margin-top: 20px;
color: #fff;
font-weight: 400;
}

.site {
color: #fff;
margin-top: 20px;
font-size: 20px;
font-weight: 700;
float: left;
}


.btn {
background-color: #D82CD1;
padding-top: 10px;
padding-bottom: 10px;
padding-left: 35px;
padding-right: 35px;
border-radius: 6px;
color: #fff;
font-size: 13px;
margin-left: 30px;
}

.texts {
    margin-left: 30px;
}

.page {
    background-color: #fff;
}

</style>