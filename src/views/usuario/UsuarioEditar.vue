<template>
  <section>
    <UsuarioForm>
      <button class="btn" @click.prevent="atualizarUsuario">Atualizar Usuáario</button>
    </UsuarioForm>
  </section>    
</template>

<script>
import UsuarioForm from "@/components/UsuarioForm.vue";

export default {
  name: "UsuarioEditar",
  components: {
    UsuarioForm
  }
};
</script>

<style>
</style>