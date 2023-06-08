<script setup>


</script>

<template>
<div class="parent-card">
   <div class="get-card">
       <h4>How it works</h4>
       <h1>Get Your gift cards in seconds, <br> easy peasy </h1>
   </div>
   <div class="share-card">
      <div class="card-one">
        <img src="@/assets/cardone.svg" />
       <span class="Arrow-up"> <img src="@/assets/ArrowOne.svg" /></span>
        <img src="@/assets/cardtwo.svg" />
       <span class="Arrow-down"> <img src="@/assets/ArrowTwo.svg" /> </span>
        <img src="@/assets/CardThree.svg" />
      </div>
   </div>
</div>

</template>

<style scoped>
.parent-card{
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  margin-top: 10%;
  padding-top: 5%;
  height: 500px;
  background-color: #F3F4F4;
}

.get-card{
  margin-bottom: 30px;
}

.get-card h4{
  margin: 0;
  color: #dc0f0f;
}

.get-card h1{
  margin: 10px 0;
}

.share-card{
  display: flex;
  justify-content: center;
  align-items: center;
  padding-top: 8px;
}

.card-one img{
    width: 300px;
    height: 200px;
 }

.Arrow-up img{
    width: 100px;
    padding-bottom: 70px;
}

.Arrow-down img{
    width: 100px;
    padding-bottom: 40px;
}

/* Responsive Styles */

@media screen and(max-width: 768px) {
  .parent-card{
    padding: 0 20px;
  }
  
  .get-card h1{
    font-size: 20px;
  }
  .share-card{
    flex-wrap: wrap;
  }
.card-one img{
    margin: 10px;
  }

}

</style>