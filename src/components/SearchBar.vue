<template>
  <div class="search">
      <form action="" class="search_form d-flex justify-content-between">
          <input type="text" placeholder="Enter keywords, skill, interest" class="search_text">
          <div>
             <button class="search_location"><i class="fas fa-map-marker-alt"></i> Location</button>
            <button class="search_submit"><i class="fas fa-search"></i></button> 
          </div>
          
      </form>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.search{
    margin: 15px 0;
}
   form{
     border: 1px solid rgba(229, 229, 229, 1); 
     border-radius: 500px;
     padding-left: 10px; 
     /* width: 95%;  */
     background: #fff;
    }
    .search_submit{
        padding: 10px 15px;
        background: transparent;
        border: none;
        border-top-right-radius: 50px;
        border-bottom-right-radius: 50px;
        background: rgba(6, 148, 42, 1);
        color: #fff;
    }
    .search_location{
        padding: 10px 15px;
        background: transparent;
        border: none;
    }
    input{
        flex-grow: 1;
        border: 0;
        border-right: 2px solid rgba(229, 229, 229, 1);
        background: transparent;
        font-size: 1px;
        padding: 0 5px;
        outline: none;
        display: inline-block;
    }
</style>