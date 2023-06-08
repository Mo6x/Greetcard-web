<script setup>


</script>


<template>
 <div class="List-items">
    <div class="Navbar-items">
        <a v-bind:href="linkUrl" class="Navbar-btn-right">Occasions
         <i class="fa fa-chevron-up"></i>
         
        </a>
         <div class="Navbar-list">
            <a v-bind:href="linkUrl">Birthday</a>
            <a v-bind:href="linkUrl">Anniversary</a>
            <a v-bind:href="linkUrl">Goodwill</a>
            <a v-bind:href="linkUrl">Festival</a>
            <a v-bind:href="linkUrl">Sympathy</a>
            <a v-bind:href="linkUrl">Love</a>
            <a v-bind:href="linkUrl">Relationship</a>
     </div>
     <a v-bind:href="linkUrl" class="Navbar-btn-right">Try Demo

     </a>
    </div>    
 </div>
</template>


<style scoped>

.Navbar-btn-right{
   justify-content: center;
   border-radius: 2px;
   width:100px;
   height:40px;
   display: flex;
   margin-top: 6%;
   align-items: center;
   border: 1px solid #ccc;
   
}
.List-items{
  display: flex;
  width: 100%;
  height: 70px;
  justify-content: center;
  align-items: center;
  
}
.Navbar-items{
   width:80%;
   height:50px;
   display: flex;
   align-items: center;
   justify-content: space-between;

}

.Navbar-list{
   width:60%;
   height:40px;
   margin-top: 6%;
   display: flex;
   justify-content: space-around;
   align-items: center;
   font-family: sans-serif;
}

.Navbar-btn-left{
   display: contents;
   align-self: flex-end;
}
</style>