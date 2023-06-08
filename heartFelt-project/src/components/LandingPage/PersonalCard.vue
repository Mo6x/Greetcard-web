<script scoped>


</script>


<template>
    <div class="gift-card">
        <div class="gift-card-one">
        <div class="card-detail">
             <h1>personalise gift card <br>
            to preference
            </h1>

          <p>
            Tap into the gift bag to share love in the most 
            amazing way. Change preference to suit that 
            special one with no extre cost.
          </p>  
          <a v-bind:href="linkUrl">Customise a card</a>
          <img src="@/assets/arrow.svg" />
        </div>

        <div class="Images-details">
            <div class="Img-images">
                <img src="@/assets/EllipseWine.svg" />
                <img src="@/assets/RectanglBlue.svg" />
                <img src="@/assets/EllipseBlue.svg" />
                <img src="@/assets/Ellipse LightBlue.svg" />
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
                <ul>
                    <li v-for="item in items" :key="item.id">{{ item.name }}</li>
                  </ul>
             </div>
             <div class="love-card">
                <img src="@/assets/piclove.svg" />
                <button class="button-field">Happy</button>
             </div>
             <img src="@/assets/blueArrow.svg" />
             <img src="@/assets/blueArrow.svg" />
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
            <a v-bind:href="linkUrl">Send a card</a>
            <img src="@/assets/arrow.svg" />
        </div>
    </div> 
    </div>
</template>


<style scoped>

.gift-card{
  display: flex;
  flex-direction: column;
  padding-top: 200px;
  justify-content: space-between;
}

.gift-card-one{
  display: flex;
  justify-content: space-evenly;
  flex-direction: row;
}

.card-detail{
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
}

.Images-details{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  margin-top: 30px;
}

.Img-images, .Icon-details, .diamon-imge{
  display: flex;
  flex-direction: row;
 width: 33.33%;
}
.Img-images img, .Icon-detailsn img, .diamon-imge img {
  
display: block;
  margin-bottom: 10px;
}

.sendimge{
  display: flex;
  justify-content: center;
  align-items: center;
}

.Icon-details{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.diamon-imge{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.Face-smile-icon{
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 10px;
}

.button-field{
  display: block;
  margin-top: 20px;
  padding: 10px 20px;
  border: none;
  background-color: #c4c4c4;
  color: #fff;
  cursor: pointer;
}

.images-details{
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: 30px;
}

.images-detail-one{
  display: flex;
  display: flex;
  justify-content: space-evenly;
  flex-direction: row;
}

.send-modal, .love-card{
  width: 33.33%;
}

.send-modaln ul, .love-card{
  list-style: none;
  padding: 0;
  margin: 0;
}

.love-card img{
  display: block;
  margin-bottom: 10px;
}

.images-details img{
  display: block;
  margin-bottom: 20px;
}

.images-aticle{
  text-align: center;
}

.images-aticle h1{
  margin: 0;
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