<script setup>

</script>

<template>

    <div class="verifed-companies">
        <div class="companies-numbers">
             <h1> 650,000+</h1> 
             <p>Verified Companies</p>
        </div>
        <div class="Companies-images">
        <img src="@/assets/apple.svg" />
        <img src="@/assets/Amazon.svg" />
        <img src="@/assets/mecorsoft.svg" />
        <img src="@/assets/mecorsoft.svg" />
        <img src="@/assets/mecorsoft.svg" />
        <img src="@/assets/Titok.svg" />
        </div>
   </div>
</template>


<style scoped>
.verifed-companies{
    height: 80px; 
    display: flex;
    width:90%;
    padding-top: 10%;
    align-items: center;
    justify-content: space-between; 
}
.companies-numbers{
    width: 30%;
    height: 120px;
    display: flex;
    flex-direction: column;
    align-items: center;
}
.companies-numbers p{
margin: 0px;
}
.Companies-images{
    width: 60%;
    height: 150px;
    display: flex;
    align-items: center;
    background-color: #B8B8B8;
}

.Companies-images img{
margin-left: 20px;
}

h1{
    color: #299E9E;
}

@media screen and(max-width: 768px) {
  .verified-companies{
    flex-wrap: wrap;
    justify-content: center;
    align-items: flex-start;
  }
}
</style>