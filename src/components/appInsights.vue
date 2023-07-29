<template>
  <div class="contact" id="Insights">
    <section class="contato" id="Resultados">
      <div class="contato-quadrado">
        <h1 class="duvida">Os Insights</h1>
        <div class="container">

          <img src="../assets/Insights.png" />
        </div>
         <h1 class="insight">O gráfico gerado pelo Xgboost (Feature Importance Plot) junto do Scatter Plot identifica as features mais relevantes e como é a divisão dos dados através da visualização dessas features em específico (V14, V10 e V4). Isso permite rastrear de forma mais acertiva quais os atributos que poderiammos olhar para tentar indicar se uma transação é fraudulenta ou não. Atributos que são menos relevantes, como (V23, V13 e V8) possuem uma sobreposição e concentração de dados que misturam entre fraudulentos e não fraudulentos, tornando imperceptível a separação desses.</h1>
      </div>
    </section>

  </div>
</template>


<script>
export default {

}
</script>


<style scoped>
.contato-quadrado {
  text-align: center;
  font-size: 30px;
  background-color: #51B797;
  align-items: center;
  padding: 30px;
  color: #F4f4f4;
}

.insight{
  text-align: center;
  font-size: 30px;
  background-color: #51B797;
  align-items: center;
  padding: 20px;
  color: #F4f4f4;
}

.container {
  display: flex;
  font-size: 13px;
  align-items: center;
  color: #F4f4f4;
  padding: 30px;
}

img {
  width: 1750px;
  align-items: center;
}
</style>