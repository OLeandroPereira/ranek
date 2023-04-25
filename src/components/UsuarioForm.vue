<template>
  <form>
    <label for="nome">Nome</label>
    <input id="nome" name="nome" type="text" v-model="nome">
    <label for="nome">email</label>
    <input id="email" name="email" type="email" v-model="email">
    <label for="senha">Senha</label>
    <input id="senha" name="senha" type="password" v-model="senha">
    <label for="cep">Cep</label>
    <input id="cep" name="cep" type="text" v-model="cep">
    <label for="rua">Rua</label>
    <input id="rua" name="rua" type="text" v-model="rua">
    <label for="cep">Número</label>
    <input id="numero" name="numero" type="text" v-model="numero">
    <label for="estado">Bairro</label>
    <input id="estado" name="estado" type="text" v-model="estado">
    <label for="cidade">Cidade</label>
    <input id="cidade" name="estado" type="text" v-model="cidade">
    <label for="estado">estado</label>
    <input id="estado" name="estado" type="text" v-model="estado">
    <div class="button">
      <slot></slot>
    </div>
  </form>
</template>

<script>
export default {};
</script>

<style>
form {
  display: grid;
  grid-template-columns: 80px 1fr;
  align-items: center;
}

.button {
  grid-column: 2;
  margin-top: 10px;
}
</style>