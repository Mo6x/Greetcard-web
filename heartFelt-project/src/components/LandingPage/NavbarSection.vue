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
  justify-content: space-between;
  align-items: center;
}

.Navbar-sect{
  flex: 1;
  padding-right: 20px;
}

.Text{
  margin: 0;
  font-size: 28px;
}
.eclipse {
  position: relative;
  margin-bottom: 20px;
}

.eclipse img{
  position: absolute;
  top: -10px;
  left: -10px;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.Paragraph {
  margin-bottom: 20px;
}

.Card-button{
  display: block;
  margin-top: 20px;  
  padding: 10px 20px;
  border: none;
  background-color: #c4c4c4;
  color: #fff;
  cursor: pointer;
}

.Cards-color{
  display: flex;
  gap: 10px;
  position: relative;
  z-index: 1;
}
.Color-green{
  width: 100px;
  height: 100px;
  background-color: green;
}

.Color-red{
  width: 100px;
  height: 100px;
  background-color: red;
}

.Color-blue{
  width: 100px;
  height: 100px;
  background-color: blue;
}

.Color-yellow{
  width: 100px;
  height: 100px;
  background-color: yellow;
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