<template>
  <div class="whoWeAre">
    <section class="quemSomos-section">
      <h1 class="quemSomos" >O time</h1>
      <div class="Wrap">
      <div class = container>
      <div class = card>
        <div class = image>
          <img href = "#" src ="../assets/Gustavo.png">
        </div>
        <div class = content>
          <h3>Gustavo Goes</h3>
          <p>Gustavo, tenho 21 anos e estou cursando Sistemas de Informação na UFMS</p>
        </div>
      </div>    
    </div>
        <div class = container>
        <div class = card>
          <div class = image>
            <img href = "#" src ="../assets/Ale.png">
          </div>
          <div class = content>
            <h3>Alexandre Diniz</h3>
            <p>Eu sou o Alexandre, tenho 20 anos e sou estudante de Ciência da Computação na UFMS</p>
          </div>
        </div>    
      </div>
              <div class = container>
          <div class = card>
            <div class = image>
              <img href = "#" src ="../assets/Joao.png">
            </div>
            <div class = content>
              <h3>João Lucas Machado</h3>
              <p>Eu sou o João Lucas, tenho 21 anos e sou estudante de Engenharia de Software na UFMS</p>
            </div>
          </div>    
        </div>
                <div class = container>
          <div class = card>
            <div class = image>
              <img href = "#" src = "../assets/Iago.png">
            </div>
            <div class = content>
              <h3>Iago Akio Saito</h3>
              <p>Eu sou o Iago, tenho 21 anos e sou estudante de Engenharia de Software na UFMS</p>
            </div>
          </div>    
        </div>
      </div>
    </section>
  </div>
</template>


<script>


export default {
  components: {
  }


}
</script>

<style scoped>
.quemSomos {
  text-align: center;
  color: #F4f4f4;
  font-size: 50px;

}

section {
  background-color: #229679;

}

.Wrap {
  display : flex;
  align-items : center;
  justify-content : center;  
  min-height : 400px;
}

.container {
  position : relative;
  width : 300px;
  display : flex;
  align-items : center;
  justify-content : center;
  flex-warp : warp;
  padding : 70px;  
}

.container .card {
  position: relative;
  max-width : 300px;
  height : 215px;  
  background-color : #fff;
  margin : 30px 10px;
  padding : 20px 15px;
  
  display : flex;
  flex-direction : column;
  box-shadow : 0 5px 20px rgba(0,0,0,0.5);
  transition : 0.3s ease-in-out;
  border-radius : 15px;
}
.container .card:hover {
  height : 320px;    
}


.container .card .image {
  position : relative;
  width : 260px;
  height : 260px;
  
  top : -40%;
  left: 8px;
  box-shadow : 0 5px 20px rgba(0,0,0,0.2);
  z-index : 1;
}

.container .card .image img {
  max-width : 100%;
  border-radius : 15px;
}

.container .card .content {
  position : relative;
  top : -140px;
  padding : 10px 15px;
  color : #111;
  text-align : center;
  
  visibility : hidden;
  opacity : 0;
  transition : 0.3s ease-in-out;
    
}

.container .card:hover .content {
   margin-top : 30px;
   visibility : visible;
   opacity : 1;
   transition-delay: 0.2s;
  
}


</style>