<template>
  <div class="screenshots">
      <div class="gore">
          <h4>App Screenshots</h4>
          <p>Most such devices are sold with several apps bundled as pre-installed software, 
           such as a web browser, email client, calendar, mapping program.</p>
      </div>
      <div class="dole">

        <div id="carouselExampleControls" class="carousel slide text-center mt-3" data-ride="carousel" data-interval="3000">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <div class="row">
            <div class="col"><img src="../assets/caroseul1.png" class="d-block w-100" alt="..."></div>
            <div class="col"><img src="../assets/caroseul2.png" class="d-block w-100" alt="..."></div>
            <div class="col"><img src="../assets/caroseul3.png" class="d-block w-100" alt="..."></div>
            <div class="col"><img src="../assets/caroseul4.png" class="d-block w-100" alt="..."></div>
            <div class="col"><img src="../assets/caroseul5.png" class="d-block w-100" alt="..."></div>

          </div>

        </div>
        <div class="carousel-item">

          <div class="row">
            <div class="col"><img src="../assets/caroseul2.png" class="d-block w-100" alt="..."></div>
            <div class="col"><img src="../assets/caroseul3.png" class="d-block w-100" alt="..."></div>
            <div class="col"><img src="../assets/caroseul4.png" class="d-block w-100" alt="..."></div>
            <div class="col"><img src="../assets/caroseul5.png" class="d-block w-100" alt="..."></div>
            <div class="col"><img src="../assets/caroseul2.png" class="d-block w-100" alt="..."></div>

          </div>
        </div>
        <div class="carousel-item">
          <div class="row">
            <div class="col"><img src="../assets/caroseul3.png" class="d-block w-100" alt="..."></div>
            <div class="col"><img src="../assets/caroseul4.png" class="d-block w-100" alt="..."></div>
            <div class="col"><img src="../assets/caroseul5.png" class="d-block w-100" alt="..."></div>
            <div class="col"><img src="../assets/caroseul1.png" class="d-block w-100" alt="..."></div>
            <div class="col"><img src="../assets/caroseul2.png" class="d-block w-100" alt="..."></div>

          </div>
        </div>
        <div class="carousel-item">
          <div class="row">
            <div class="col"><img src="../assets/caroseul4.png" class="d-block w-100" alt="..."></div>
            <div class="col"><img src="../assets/caroseul5.png" class="d-block w-100" alt="..."></div>
            <div class="col"><img src="../assets/caroseul1.png" class="d-block w-100" alt="..."></div>
            <div class="col"><img src="../assets/caroseul2.png" class="d-block w-100" alt="..."></div>
            <div class="col"><img src="../assets/caroseul3.png" class="d-block w-100" alt="..."></div>

          </div>
        </div>
        <div class="carousel-item">
          <div class="row">
            <div class="col"><img src="../assets/caroseul5.png" class="d-block w-100" alt="..."></div>
            <div class="col"><img src="../assets/caroseul1.png" class="d-block w-100" alt="..."></div>
            <div class="col"><img src="../assets/caroseul2.png" class="d-block w-100" alt="..."></div>
            <div class="col"><img src="../assets/caroseul3.png" class="d-block w-100" alt="..."></div>
            <div class="col"><img src="../assets/caroseul4.png" class="d-block w-100" alt="..."></div>

          </div>
        </div>
      </div>
      <div class="text-center mt-5"> <a href="#carouselExampleControls" data-slide="prev">
          <img src="../assets/left.png" alt="" class="prevNext">
        </a>
        <a href="#carouselExampleControls" data-slide="next">
          <img src="../assets/right.png" alt="" class="prevNext">
        </a>
      </div>
    </div>
        <!-- kraj karoseula -->
</div>
      </div>
  
</template>

<script>
export default {
  name: 'Screenshots',
  mounted(){
    this.$nextTick(() => {
        
        //Jquery here
        $('.carousel').carousel({
  interval: 3000
})


    });
  },
  
  
}
//caroseul


</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    /* caroseul */
   
    /* kraj caroseula */
    .screenshots {
      width: 100%;
      height: 980px;
      /* justify-content: center; */
    }

    .gore{
      width: 804px;
      height: 150px;
      margin: 20px auto;

    }
    .dole {
      width: 1890px;
      height: 980px;
      margin: 0 auto;
      
    }
    
    #container-div{
      width: 100%;
      height: 100%;
    
    }
    .prevNext {
      transition: 0.5s
    }
    .prevNext:active {
      transform: scale(1.1)
    }
   
    
</style>