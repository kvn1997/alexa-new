<template>
  <div class="home">
   
    
  
  <div id="app">
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="4000"
      controls
      indicators
      background="#ababab"
      img-width="1024"
      img-height="460"
      style="text-shadow: 1px 1px 2px #333;"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >
  <b-carousel-slide>
        <template v-slot:img>
          <img
            class="d-block w-100 fluid max-width: 100%"
            width="1350"
            height="620"
            src="@/assets/imgs/2.jpg"
            alt="image slot"
          >
        </template>
      </b-carousel-slide>
      <b-carousel-slide>
        
        <template v-slot:img>

          <img

            class="d-block w-100 fluid max-width: 100%"
            width="804"
            height="620"
            src="@/assets/imgs/3.jpg"
            alt="image slot"
          >
        </template>
      </b-carousel-slide>
      <b-carousel-slide>
        <template v-slot:img>
          <img
            class="d-block w-100 fluid max-width: 100%"
            width="1024"
            height="620"
            src="@/assets/imgs/4.jpg"
            alt="image slot"
          >
        </template>
      </b-carousel-slide>
      </b-carousel>
  
    </div>  
    
  </div>
</template>
 <script>
    export default {
      name: 'home',
      
    }
  </script>
