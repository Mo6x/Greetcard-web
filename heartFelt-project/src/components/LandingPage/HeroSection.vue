<script setup>

</script>

<template>

<div class="Navbar-section">
     <div class="Navbar-sect">
         <h1 class="Text">Get digital Gifts <br />Cards at Ease</h1>
         <div class="eclipse"><img src="@/assets/Vector.png" /></div>
         <p class="Paragraph">
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

.Text{
  margin: 0;
  font-size: 60px;
}
.eclipse img{
  top: 40px;
  left: 10px;
  
  
 
}

.Paragraph {
  margin-bottom: 20px;
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
  display: flex;
  margin-right: 10%;
  overflow: auto;
}

.Color-green{
  width: 200px;
  height: 250px;
  right: 10px;
  background-color: #7DD1D3;
  z-index: 4;
}

.Color-red{
  width: 200px;
  height: 170px;
  background-color: red;
  z-index: 3;
}

.Color-blue {
  width: 200px;
  height: 250px;
  background-color: #1F3C76;
  z-index: 2;
}

.Color-yellow{
  width: 200px;
  height: 170px;
  bottom: 20px;
  background-color: yellow;
  z-index: 1;
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