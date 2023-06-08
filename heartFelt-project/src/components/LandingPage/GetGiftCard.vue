<script setup>


</script>

<template>
<div class="parent-card">
   <div class="get-card">
       <h4>How it works</h4>
       <h1>Get Your gift cards in seconds easy peasy </h1>
   </div>
   <div class="share-card">
      <div class="card-one">
        <img src="@/assets/cardone.svg" />
        <img src="@/assets/ArrowOne.svg" />
        <img src="@/assets/cardtwo.svg" />
        <img src="@/assets/ArrowTwo.svg" />
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
}

.get-card{
  margin-bottom: 30px;
}

.get-card h4{
  margin: 0;
  color: #888;
}

.get-card h1{
  margin: 10px 0;
}

.share-card{
  display: flex;
  justify-content: center;
  align-items: center;
}

.card-one img{
  margin: 0 10px;
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