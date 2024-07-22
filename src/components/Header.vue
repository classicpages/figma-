<template>
    <nav class="flex">
        <p class="site"> <img src="/src/assets/chef-hat (2) 1.png"> Foo</p>
            <div class="flex navbar">
              <div class="navbars">Home</div>
              <div class="navbar">Menu</div>
              <div class="navbar">Contact</div>
              <div class="navbar">Shop</div>
            <div class="texts"><img src="/src/assets/Vector.png"><input class="search" type="search"
                 placeholder="search"><img src="/src/assets/Shopping cart.png"></div> 
            </div>
    </nav>
</template>

<style scoped>
.navbar {
width: 100px;
height: 58px;
text-align: right;
margin-left: 50px;
display: flex;
margin-top: 20px;
}

.search {
    margin-top: 20px;
    padding-top: 8px;
    padding-left: 5px;
    padding-bottom: 8px;
    padding-right: 5px;
}

.navbars {
margin-left: 500px;
margin-top: 20px;

}
.site {
color: #D82CD1;
margin-top: 20px;
margin-left: 20px;
font-size: 15px;
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

</style>