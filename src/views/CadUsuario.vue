<template>
  <div class="livro">
    <label for="">Usuário</label>
  </div>
  <router-link to="/cadastro">
    <button>←VOLTAR</button>
  </router-link>
</template>
<style scoped>
.livro {
  position: absolute;
  width: 920px;
  height: 310px;
  left: 350px;
  top: 291px;

  background: #d9d9d9;
  border-radius: 49px;
}
.livro label {
  position: absolute;
  width: 120px;
  height: 44px;
  left: 400px;
  top: 30px;

  font-family: "Montserrat";
  font-style: normal;
  font-weight: 900;
  font-size: 30px;
  line-height: 44px;

  text-align: center;

  color: #6c3a3a;
}
.livro ul {
  position: absolute;
  width: 117px;
  height: 29px;
  left: 0px;
  top: 80px;

  font-family: "Montserrat";
  font-style: normal;
  font-weight: 400;
  line-height: 29px;
  text-align: left;
  list-style-type: none;

  color: #6c3a3a;
}
button {
  position: absolute;
  width: 80px;
  height: 30px;
  left: 380px;
  top: 240px;

  font-family: "Montserrat";
  text-align: center;
  border-radius: 24px;
  background-color: #6c3a3a;
  color: #ffffff;
}
</style>