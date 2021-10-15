<template>
  <div>
  <p>Componente de Mensagem</p>
  <form id="burger-form">
    <div class="input-container">
        <label for="nome">Nome do Cliente</label>
        <input type="text" id="nome" name="nome" v-model="nome" placeholder="Nome do Cliente">
    </div>
    <div class="input-container">
        <label for="pao">Escolha o pão: </label>
        <select id="pao" name="pao" v-model="pao">
            <option value="">Selecione seu pão</option>
        </select>
    </div>
    <div class="input-container">
        <label for="carne">Escolha a carne do seu burger: </label>
        <select id="carne" name="carne" v-model="carne">
            <option value="">Selecione o tipo de carne</option>
            <option value="">Picanha</option>
        </select>
    </div>
    <div class="input-container">
        <label for="opcionais">Selecione os opcionais: </label>
        <div class="checkbox-container">
        
        </div>
    </div>
  </form>
  </div>
</template>
<script>
export default{
    name:"BurgerForm"
}
</script>
<style scoped>
</style>