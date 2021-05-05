<template>
<div class="topo">
  <h1>Curso de Inglês</h1>
  <h3>Desenvolvido por: {{autor}}</h3>
  <div v-if="detalhes">
    <h2>Mega Promoção</h2>
    <h2>De {{preço}} R$ por apenas {{preçoComDesconto}} R$ </h2>
  </div>  
 <button>acessar curso de {{curso}}</button>
</div>
</template>

<script>
export default {
  props: ["curso","detalhes"],
  data(){
    return{
    preço: 499.00,
    preçoComDesconto: 299.00,
    autor: 'Italo'
    }
  }
}
</script>

<style scoped>
*{
  margin: 0;
}
.topo{
  padding: 10px;
  background-color: rgb(199, 53, 82);
  color: azure;
}
h1{
  margin-bottom: 10px;
}
h2{
  margin-bottom: 5px;
}
h3{
  margin-bottom: 10px;
}
button{
  margin-top: 10px;
  width: 280px;
  height: 40px;
  border: none;
}


</style>
