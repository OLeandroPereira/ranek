<template>
  <div>
    <p>{{ produto.descricao }}</p>
    <p>{{ produto.preco }}</p>
  </div>
</template>

<script>
export default {
  name: "ProdutoItem",
  props: ["produto"]
};

</script>

<style>

</style>