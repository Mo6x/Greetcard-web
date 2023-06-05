<script setup>



</script>

<template>
<div class="NavBar"> 
    <header>
        <div class="nav-header">
            <img src="@/assets/heartfelt-logo.svg" />
            <a v-bind:href="linkUrl">About</a>
            <a v-bind:href="linkUrl">Pricing</a>
            <a v-bind:href="linkUrl">Try Demo</a>
        </div>
        <div class="">
            <input type="text" v-model="input" placeholder="Search " />
            <a v-bind:href="linkUrl">Sign in</a>
            <button class="Card-button">
                Send a card
            </button>
        </div>
    </header>

    <div class="container">
        <div class="Navbar-items">
            <a v-bind:href="linkUrl" class="Navbar-btn-right">Occasions</a>
             <div class="Navbar-list">
                <a v-bind:href="linkUrl">Birthday</a>
                <a v-bind:href="linkUrl">Anniversary</a>
                <a v-bind:href="linkUrl">Goodwill</a>
                <a v-bind:href="linkUrl">Festival</a>
                <a v-bind:href="linkUrl">Sympathy</a>
                <a v-bind:href="linkUrl">Love</a>
                <a v-bind:href="linkUrl">Relationship</a>
             </div>
            <a v-bind:href="linkUrl" class="Navbar-btn-left">Try Demo</a>
       </div>

        <div class="Navbar-section">
           <div class="Navbar-sect">
            <h1 class="Text">Get digital Gifts <br />Cards at Ease</h1>
            <img src="@/assets/Vector.png" />
            <p class="Paragraph">
                Express love to friends and family all over the worlds,
                <br />with special memories of gifts.
            </p>
             <button class="Card-button">
                 Send a card
             </button>
           </div>

           <div class="Cards-color">
             <div class="Color-green">dsss</div>
             <div class="Color-red"></div>
             <div class="Color-blue"></div>
             <div class="Color-yellow"></div>
           </div>
        </div>

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

        <div class="Cards-usages">
             <div class="Cards-uses">
                 <h1 class="H-1">Personalise gift cards to preference</h1>
                 <p class="P-tage">
                    Top into the gift bag to share love in the most 
                    amazing way. Change prefernce o suit hat special 
                    one  with no extra cost.
                 </p>
                 <span>Customise a card</span>
             </div>
        </div> 
        <section class="row">

        </section>




    </div>
    <footer>

    </footer>
    </div>
  </template>
  
  <style scoped>
  .NavBar {
    display: flex;

    flex-direction: column;

    background-color: white;
    height: auto;
    width: 100%;
    align-items: center;
    justify-content: center;
  }
  .container{
    width:85%;
    height:auto;
    background-color: red;

  }
header{
    width:100%;
    height: 100px;
    background-color: white;
    display: flex;
    justify-content: center;
}
.nav-header{
    width: 90%;
    height: 100%;
    background-color: pink;
}
footer{
    width:100%;
    height: 150px;
    background-color: red; 
}
  .Navbar-items{
    display: flex;
    flex-wrap: wrap;
    padding-top: 5%;
    align-items: center;
    justify-content: center;
    color: #0D3336;
    font-size: 130%;
    font-weight: lighter;
    width:100%;
    background-color: pink;
  }
 
  .Navbar-btn-right{
      color: #0D3336;
      border: 1px solid blue;
      padding: 20px 50px;
      font-size: 30px;
      background-color: white;
  }

  .Navbar-btn-left{

      color: #0D3336;
      border: 1px solid blue;
      padding: 20px 50px;
      font-size: 30px;
      background-color: white;
  }
  

  .Navbar-list{
    display: flex;
    gap: 7%;
    align-items: center;
    justify-content: center;
    width: 70%;
  }

.Navbar-section{
    display: flex;
    padding-top: 100px;
    display: flex;
    justify-content: space-between;
}



.Cards-color{
    position: relative;
    display: flex;

 
  

    padding-right: 200px;
   
}

.Color-green{
    height: 300px;
    width: 300px;
    background-color: #299E9E;
    z-index: 1;
    position: absolute;
    top: 110px;
    left: -200px;
}

.Color-yellow{
    height: 200px;
    width: 250px;
    background-color: #EF4444;
    z-index: 3;
    position: absolute;
    top: 20px;
    left: -250px;
}

.Color-red{
    height: 200px;
    width: 250px;
    background-color: #EF4444;
    z-index: 3;
    position: absolute;
    top: 250px;
    left: -220px;
}

.Color-blue{
    height: 350px;
    width: 270px;
    background-color: blue;
    z-index: 7;
    position: absolute;
    top: 70px;
    left: -420px;
}

.Text{
    font-size: 50px;
    margin-bottom: 4px;
}
.Paragraph{
    margin-top: 0px;
}

.verifed-companies{
    display: flex;
    width:100%;
    height: auto;
    background-color: white;
    align-items: center;
    justify-content: space-between;
    margin-top: 300px;
   
}
.companies-numbers{
    width: 30%;
    height: 150px;
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
}

.Companies-images img{
margin-left: 20px;
}
  </style>
  