<template>
  <section>
    <h1>Login</h1>
    <form>
      <label for="email">Email</label>
      <input type="email" name="email" id="email" v-model="login.email">
      <label for="senha">Senha</label>
      <input type="password" name="senha" id="senha" v-model="login.senha">
      <button class="btn" @click.prevent="">logar</button>
    </form>
    <p class="pedeu">
      <a href="/" target="_blank">Perdeu a senha? Clique aqui.</a>
    </p>
  </section>
</template>

<script>
export default {
  data() {
    return {
      login: {
        email: "",
        senha: ""
      }
    };
  }
};
</script>

<style>
</style>