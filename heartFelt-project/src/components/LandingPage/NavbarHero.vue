<script setup>



</script>

<template>
    <div class="NavBar-hero"> 
            <div class="Navbar-head">
                <img class="HeartFelt" src="@/assets/heartfelt-logo.svg" />
                <a v-bind:href="linkUrl">About</a>
                <a v-bind:href="linkUrl">Pricing</a>
                <a v-bind:href="linkUrl">Try Demo</a>
            </div>
            <div class="Navbar-search">
                <label>
                    <input type="text" v-model="input" placeholder="Search " />
                </label>
                <div class="linkt">
                    <a v-bind:href="linkUrl">Sign in</a>
                    <button class="Card-button">
                        Send a card
                    </button>

                </div>
              
            </div>
    </div>    

</template>


<style scoped>
  .NavBar-hero{
    display: flex;
    width: 100%;
    
    justify-content: center;
  }
    .Navbar-head{
        display: flex;
        align-items: center;
        height: 70px;
        width:55%;
    }
    .Navbar-head a{
        padding-left: 70px;
        color: #003366;
        font-family: sans-serif;
    }

    .Navbar-search{
        display: flex;
        align-items: center;
        width:35%;
        background-color: white;
        justify-content: flex-end;
    }
        
.Navbar-search label{
    width:300px;
    height:40px;
    background-color: white;
    display: flex;
    justify-content: flex-end;
    border: 1px solid #ccc;
}
.Navbar-search label input{
width:85%;
height:36px;
background-color: unset;
border: 0px;
outline: none;
}
.linkt{
    margin-left: 10px;
    width:40%;
    height: 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.linkt a{
    width:40%;
    height: 36px;
    background-color: #ccc;
    display: flex;
    align-items: center;
    border-radius: 3px;
    justify-content: center;
    
}
.linkt button{
    width:50%;
    border-radius: 3px;
    height: 36px;
    background-color: #299E9E;
    border: 0px;
    color: white;
}
  
</style>