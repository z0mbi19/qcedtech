<template>
  <q-page-container class="flex flex-center">
    
    <div class="row" id="home">
      <div class="col-8" >
        <h3 class="texto-principla" width="100%" >Consultancy and software factory</h3>
        <div class="row " >
          <q-btn class="btn-talk">
            <a href="mailto:victor@qcedtech.com" >Talk to us</a>
          </q-btn>

        </div>
      </div>
      <div class="col" >
        <img src="../assets/international.png" width="100%"/>
      </div>
        <div class="">
          
        </div>
    </div>
  </q-page-container>
  
</template>

<script>
export default {
  name: 'PageIndex'
}
</script>

<style>
div {
  padding: 10px;
}
.texto-principla{
  text-align: center;
}
#home{
  display: flex;
  align-items: center;

}
.btn-talk{
  display: flex;
  align-content: center;
  width: 100%;
}
</style>