<script>
import BlocoNovo from "@/components/BlocoNovo.vue";
export default {
  components: { BlocoNovo },
};
</script>
<template>
  <main id="content" class="main-itens">
    <p class="text-select">Selecione o curso Livre que deseja....</p>
    <p class="text-interesse">Curso de interesse</p>
    <input type="search" id="txtBusca" placeholder="Buscar..." />
    <button id="btnBusca">Buscar</button>
    <div id="areas">
      <BlocoNovo cor="a" nome="Exatas" />
      <BlocoNovo cor="b" nome="Saúde" />
      <BlocoNovo cor="c" nome="Direito/Comunicação" />
    </div>
  </main>
</template>

<style>
#areas {
  margin-top: 100px;
  display: flex;
  flex-wrap: wrap;
}



.text-select {
  font-size: xx-large;
}

.text-select {
  font-size: larger;
}

.main-itens {
    color: rgb(0, 0, 0);
  display: flex;
  flex-direction: column;
  align-items: center;
}

.main-itens input {
  color: rgb(0, 0, 0);
  margin: 10px auto;
  height: 30px;
  width: 500px;
  border-radius: 10px;
  padding-left: 10px;
  border: 0;
}

.main-itens button {
  background-color: #ae97db;
  border-radius: 20px;
  width: 140px;
  height: 30px;
  border: 0;
}
</style>
