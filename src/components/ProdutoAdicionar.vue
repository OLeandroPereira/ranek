<template>
  <section>
    <h2>Adicionar Produto</h2>
    <UsuarioProduto />
  </section>
</template>  

  <script>
    import ProdutoAdicionar from '@/components/ProdutoAdicionar.vue';
    export default {
      name: 'ProdutoAdicionar',
      component: {
        UsuarioProduto
      }
    };
  </script>
