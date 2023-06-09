<script setup>

</script>

<template>

<div class="Navbar-section">
     <div class="Navbar-sect">
         <h1>Get digital Gifts <br />Cards at Ease</h1>
         <img src="@/assets/Vector.png" />
         <p>
             Express love to friends and family all over the worlds,
             <br />with special memories of gifts.
         </p>
          <button class="Card-button">
              Send a card
          </button>
    </div>

 
    <div class="Cards-color">
          <div class="Color-green"></div>
          <div class="Color-red"></div>
          <div class="Color-blue"></div>
          <div class="Color-yellow"></div>
    </div>
</div>
</template>


<style scoped>

.Navbar-section{
  display: flex;
  padding-top: 10%;
  flex-direction: row;
  justify-content: space-between;
}

.Navbar-sect{
margin-left: 10%;
}

.Navbar-sect h1{
font-size: 60px;
}
.Navbar-sect img{
   display: flex;
   justify-content: end;
  margin-left: 9%;
   margin-top: -40%;
  }

 .Navbar-sect p{
  margin-top: 15%;
  font-size: 20px;
  }


.Card-button{
  width:30%;
  border-radius: 3px;
  height: 36px;
  background-color: #299E9E;
  border: 0px;
  color: white;
}

.Cards-color{
  padding-top: 5%;
  display: flex;
  margin-right: 10%;
  margin-left: -10%;
  overflow: auto;
  height: 400px;
}

.Color-green{
  width: 200px;
  height: 250px;
  align-content: center;
  margin-right: -10%;
  margin-left: 15%;
  background-color: #7DD1D3;
  z-index: 3;
}

.Color-red{
  width: 200px;
  height: 200px;
  margin-top: -100px;
  background-color: red;
  z-index: 2;
}

.Color-blue {
  width: 200px;
  height: 250px;
  margin-left: -15%;
  background-color: #1F3C76;
  z-index: 1;
}

.Color-yellow{
  width: 200px;
  height: 200px;
  bottom: 20px;
  margin-bottom: -10%;
  margin-top: 15%;
  margin-left: -40%;
  background-color: yellow;
  z-index: 2;
}


/* Responsive Styles */

@media screen and(max-width: 768px) {
  
.Navbar-section{
    flex-direction: column;
  }

  .Navbar-sect{
    padding-right: 0;
    text-align: center;
    margin-bottom: 20px;
  }

  .Text{
    font-size: 24px;
  }

  .Cards-color{
    justify-content: center;
    gap: 20px;
  }
}
</style>