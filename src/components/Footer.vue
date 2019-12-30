<template>
    <div>
    <section id="subscribe">
      <div class="container-fluid">
        <div class="sub">
          <div class="letters">
            <span class="text-white">Subscribe to get the latest updates right in your inbox </span>
          </div>
          <div class="form">
             <div class="input-group my-3">
                                   
                             <input type="text" class="" id="group-username-1" placeholder="Enter Your Email.....">
                                    <div class="input-group-append">
                                        <button type="submit" class="btn btn-primary text-uppercase">submit</button>
                                    </div>
                                </div>
          </div>
        </div>
      </div>
      </section>  
      <footer class="bg-dark">
        <div class="container-fluid">
          <div class="flex">
          <div class="fess">
            <span class="ml-3 text-white">Follow us on: <i class="fab fa-facebook ml-2 mr-3"></i><i class="fab fa-twitter mr-3"></i><i class="fab fa-pinterest mr-3"></i><i class="fab fa-google mr-3"></i></span>
          </div>

          <div class="second">
            <span class="text-white mr-3">c 2017 Food Chef. All right reserved | Designed by <a href="#" class="text-danger">W3layouts</a></span>
          </div>
          </div>
        </div>
        
        </footer>  
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

#subscribe {
  background: tomato;
  height: 30vh;
}

input {
  background: rgb(219, 148, 135);
}

.sub {
   flex-direction: column;
   align-items: center;
   height: 25vh;

}

.letters {
  font-size: 15px;
}

::placeholder {
  padding-left: 10%;
}

.flex {
  display: grid;
  grid-template-columns: repeat(1, 1fr);
}

@media screen and (min-width: 576px){
    /* 576px and Up */
    
  }

  @media screen and (min-width: 768px){
    /* 768px and up */

    .sub {
      display: flex;
      justify-content: space-around;
      flex-direction: row;
      align-items: center;
      height: 30vh;

    }

    .flex {
  display: flex;
  justify-content: space-between;
}
   

   
  }

  @media screen and (min-width: 998px){
    /* 998px and up */
   
  }
  @media screen and (min-width: 1200px){
    /* 1200px and up */
   
  }
</style>