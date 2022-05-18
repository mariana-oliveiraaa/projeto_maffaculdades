<script>
import BlocoNovo from "@/components/BlocoNovo.vue";
export default {
  components: { BlocoNovo },
};
</script>
<template>
  <main id="content" class="main-itens">
    <p class="text-select">Selecione o curso que deseja....</p>
    <input type="search" id="txtBusca" placeholder="Pesquisar" />
    <button id="btnBusca">Buscar</button>
    <div id="areas">
      <BlocoNovo cor="a" nome="EXATAS" />
      <BlocoNovo cor="b" nome="SAÚDE" />
      <BlocoNovo cor="c" nome="DIREITO/COMUNICAÇÃO" />
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
   font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
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
