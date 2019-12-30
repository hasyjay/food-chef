<template>
    <div>
  <!-- navbar -->
  <body>
      
 
    <nav class="navbar py-3 navbar-light navbar-expand-sm background text-white ">
    <!-- logo -->

    <a  href="#" class="navbar-brand"><img src="../assets/images/foodchef logo.png" class="img-fluid  h-logo"  width="200px"></a>
    <button type="button" class="navbar-toggler margin bg-white" data-toggle="collapse" data-target="#navbarLinks">
<span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse text-white" id="navbarLinks">

        <ul class="navbar-nav end navigation text-white ">
            <li class="nav-item active color"><a href="#" class="nav-link text-uppercase text-white ">Home</a></li>
            <li class="nav-item text-uppercase text-primary"><a href="#about" class="nav-link text-white">About</a></li>
            <li class="nav-item text-uppercase"><a href="#service" class="nav-link tex-uppercase text-white">Services</a></li>
            <li class="nav-item"><a href="#team" class="nav-link text-uppercase text-white">Team</a></li>
            <li class="nav-item"><a href="#our-food" class="nav-link text-uppercase text-white">Our Food</a></li>
            <li class="nav-item"><a href="#carousel" class="nav-link text-uppercase text-white">Testimonials</a></li>
            <li class="nav-item"><a href="#contact" class="nav-link text-uppercase text-white">Contact</a></li>
        </ul>
    </div>
</nav>
<section id="sub-heading" class="mt-5 pt-5">
<div class="container mt-5 pt-5">
    <div>
        <h2 class="text-white mt-5 pt-3">WELCOME TO OUR RESTAURANT</h2>
    </div>
    <div>
        <p class="text-muted pt-3">Lorem ipsum dolor sit amet.</p>
    </div>
    <div class="row holder">
        <div class="col">
            <button class="btn btn-warning">Learn More</button>
        </div>
        <div class="col  ">
            <span class="w-5 text-white bg-white ml-5 spaan"></span>
        </div>
    </div>
    <div class="logo">
        <img src="../assets/images/drawing-1.svg" alt="" class="img-fluid text-muted">
    </div>
</div>
</section>
 </body>
 
    <!-- end of navbar -->
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

body {

background-position-y: 10%;
height: 120vh;
}
section #sub-heading  {
    margin-top: 100%;
}

.background {
    background:rgba(44, 43, 43, 0.897);
    
}
h2 {
    font-size: 270%;
}
.holder {
    position: relative;
}
nav {
    position: fixed;
    width: 100%;
    margin-top: -14%;
    z-index: 999;
}
li {
    font-size: 8px;
}
.spaan {
    position: absolute;
    width: 40%;
    height: 0.3vh;
    right: 80%;
    top: 40%;
    background: white;
}


 @media screen and (min-width: 576px){
    /* 576px and Up */
   .navigation {
      margin-left: 40%;
      color: white;
      font-size: 20px;
    }
    ul li:hover {
         background: black;
         font-size: 20px; 
         cursor: pointer;
    }
    .holder {
    position: relative;
}

.spaan {
    position: absolute;
    width: 50%;
    height: 0.3vh;
    right: 105%;
    top: 40%;
}
nav {
    position: fixed;
    width: 100%;
    margin-top: -8%;
}
.h-logo {
    margin-left: 50%;
}
  }

  @media screen and (min-width: 768px){
    /* 768px and up */
   
     .navigation {
      margin-left: 40%;
    }
    .holder {
    position: relative;
}

.spaan {
    position: absolute;
    width: 50%;
    height: 0.3vh;
    right: 110%;
    top: 40%;
}
nav {
    position: fixed;
    width: 100%;
    margin-top: -8%;
}
   
  }

  @media screen and (min-width: 998px){
    /* 998px and up */
    .navigation {
      margin-left: 50%;
      color: white;
      font-size: 20px;
    }
    .holder {
    position: relative;
}

.spaan {
    position: absolute;
    width: 50%;
    height: 0.3vh;
    right: 120%;
    top: 40%;

}
nav {
    position: fixed;
    width: 100%;
    margin-top: -6%;
}
  }
  @media screen and (min-width: 1200px){
    /* 1200px and up */
    .navigation {
      margin-left: 60%;
    }
    .holder {
    position: relative;
}

.spaan {
    position: absolute;
    width: 50%;
    height: 0.3vh;
    right: 125%;
    top: 40%;
}
nav {
    position: fixed;
    width: 100%;
    margin-top: -4%;
}
  }
</style>