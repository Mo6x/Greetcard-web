<script scoped>


</script>


<template>
    <div class="gift-card">
        <div class="gift-card-one">
        <div class="card-detail">
             <h1>personalise gift cards <br>
            to preference
            </h1>
           <p>
            Tap into the gift bag to share love in the most <br> 
            amazing way. Change preference to suit that  <br> 
            special one with no extre cost.
          </p>  
          <a v-bind:href="linkUrl">Customise a card</a>
          <img src="@/assets/arrow.svg" />
        </div>

        <div class="Images-details">
            <div class="Img-images">
              <div class="imges-color">
                <img src="@/assets/EllipseWine.svg" />
                <img src="@/assets/RectanglBlue.svg" />
                <img src="@/assets/EllipseBlue.svg" />
                <img src="@/assets/Ellipse LightBlue.svg" />
               </div>

                <img src="@/assets/Gallary.svg" />


                <span class="sendimge">
                    <img src="@/assets/sendImge.svg" />
                </span>
            </div>

              <div class="Icon-details">
                <img src="@/assets/pencil.svg" />
                <img src="@/assets/Arrow..svg" />
                <img src="@/assets/phone.svg" />
                <img src="@/assets/map.svg" />
              </div>
              <div class="diamon-imge">
                <span class="Face-smile-icon">
                <img src="@/assets/facesmile.svg" />
                <img src="@/assets/smile.svg" />
                <img src="@/assets/face.svg" />
            </span>
             <span class="text-size">
                 <h1>Wishes</h1>
                 <h2>Wishes</h2>
                 <h3>Wishes</h3>
                 <h4>Wishes</h4>
             </span>
                <img src="@/assets/diamon.svg" />
                <button class="button-field">Happy</button>
              </div>
        </div>
       </div> 
        <div class="images-details">
           <div class="images-detail-one">
             <div class="send-modal">
              <a v-bind:href="linkUrl">Recipient (s)</a>
               <div class="blackArrow">
                 <img src="@/assets/blackArrow.svg" />
              </div>
              <form action="/submit" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
            
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
            
                <label for="name">Amount:</label>
                <input type="text" id="name" name="name" required>

                <label for="name">Delivery:</label>
                <input type="text" id="name" name="name" required>
            
                <input type="submit" value="Submit">
              </form>
             </div>
             <div class="love-card">
                <img src="@/assets/piclove.svg" />
                <button class="button-field">Happy</button>
             </div>
             <div class="Arrow-1">
             <img src="@/assets/blueArrow.svg" />
             <img src="@/assets/blueArrow.svg" />
            </div>
        </div>
        <div class="images-aticle">
            <h1>Share to loved ones on <br>
            special moments
            </h1>
            <p>
              Tap into the gift bag to share love in the most <br>
              amazing way. Change preference to suit that <br>
              special one with no extra cost.  
            </p>
            <div class="send-link">
            <a v-bind:href="linkUrl">Send a card</a>
            <img src="@/assets/arrow.svg" />
          </div>
        </div>
    </div> 
    </div>
</template>


<style scoped>

.gift-card{
  display: flex;
  flex-direction: column;
  margin-top: 20%;
  justify-content: space-between;
}

.gift-card-one{
  display: flex;
  margin-left: 10%;
  justify-content: space-between;
}

.card-detail h1{
   font-size: 50px;
}

.card-detail p{
  width: 500px;
  color: #6B6B6B;
  font-size: 25px;
}

.card-detail a{
  display: flex;
 color: #299E9E;
  font-size: 25px;
}


.Images-details{
  margin-right: 10%;
}

.Img-image{
  display: flex;
}


.images-details{
  display: flex;
  margin-top: 10%;
  justify-content: space-between;
}

.images-detail-one{
  margin-left: 10%;
}

.send-modal{
  display: flex;
  width: 300px;
  height: 100px;
  justify-content: space-between;
}

.send-modal form{
  flex: row;
  padding-bottom: 10%;
}

.send-modal a{
  font-size: 20px;
}

.send-modal blackArrow{
 align-items: center;
}

.images-aticle{
  margin-right: 10%;
}

.images-aticle h1{
     font-size: 50px;
}

.images-aticle p{
  width: 500px;
  font-size: 25px;
  color: #6B6B6B;
}

.love-card{
  height: 500px;
  width: 350px;
  margin-left: 70%;
  border: border-box solid 1px black;
  border-radius: 5%;
  background-color: aqua;
}

.love-card button{
  display: flex;
  width: 50%;
  height: 30px;
  margin-top: 10%;
  margin-left: 12%;
  text-align: center;
}

 .Arrow-1{
  margin-left: 50px;
}

.love-card img{
  padding-left: 40px;
  padding-top: 40px;
 
}

.send-link{
  display: flex;
  justify-content: baseline
  }

  .send-link a{
    font-size: 25px;
     color: #299E9E;
  }

  .send-link img{
    height: 40px;
   
  }

/* Responsive Styles */

@media screen and(max-width: 768px) {
  
.Images-details, .images-details{
    flex-wrap: wrap;
    justify-content: center;
  }

  
.Img-images, .Icon-details, .diamon-imge .send-modal,.love-card{
    width: 100%;
  }

  .card-detail, .images-aticle{
    padding: 0 20px;
  }

  
.Images-details img, .Icon-detailsimg,.diamon-imge img, .love-card img{
    margin-left: auto;
    margin-right: auto;
  }

.button-field{
    width: 100%;
  }

  .images-details img{
    margin-left: 20px;
    margin-right: 20px;
  }

}
</style>