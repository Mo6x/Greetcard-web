<script setup>

</script>

<template>
   <div class="heartfelt">
      <div class="shared-card">
         <div class="fast-share">
              <h1>The fastest way to share <br>
                gift cards to people
            </h1>
            <p>
                Whether you're celebrating a loved one or <br>
                family, Heartfelt helps you to share the love <br>
                and care virtully. Nothing is not a barrier.
            </p>
            <div class="share-info">
            <img src="@/assets/markgood.svg" />
            <a v-bind:href="linkUrl">Purchase at Discounts</a>
            </div>
            <div class="share-info">
                <img src="@/assets/markgood.svg" />
                <a v-bind:href="linkUrl">Share to muiltple people</a>
                </div>
                <div class="share-info">
                    <img src="@/assets/markgood.svg" />
                    <a v-bind:href="linkUrl">Deliver at any location</a>
                    </div>
         </div>
         <div class="share-imge">
            <img src="@/assets/handimg.svg" />
         </div>
      </div>

      <div class="select-card">
           <div class="select-heartfelt">
                 <h1>Why people are choosing Heartfelt</h1>
                 <p>Here is what they have to say.</p>
           </div>

      </div>
   </div>
  
</template>

<style scoped>
.heartfelt{
    margin-top: 10%;
}

.shared-card{
    display: flex;
    margin-left: 10%;
    justify-content: space-between;
}

.fast-share{
   font-size: 25px;
}

.fast-share p{
  color: #6B6B6B;
}

.share-info a{
   color: #6B6B6B;
   margin-left: 4%;
}

.share-info{
    display: flex;
}

.share-imge img{
   margin-left: -30%;
   height: 400px;
}

.select-card{
    margin-top: 10%;
    background-color: aqua;
}

.select-heartfelt h1{
    justify-content: center;
    text-align: center;
     font-size: 50px;
    text-size-adjust: 50px;
}

.select-heartfelt p{
    justify-content: center;
    text-align: center;
    color: #6B6B6B;
}

</style>