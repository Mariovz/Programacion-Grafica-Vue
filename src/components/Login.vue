<template>
  <div class="login">
    <h1 class="title">INGRESAR A SU CUENTA</h1>
    <form action class="form">
      <label class="form-label" for="#email">USUARIO</label>
      <input class="form-input" type="email" id="email" required placeholder="USUARIO">
      <label class="form-label" for="#password">CONTRASEÑA</label>
      <input class="form-input" type="password" id="password" placeholder="CONTRASEÑA">
      <input class="form-submit" type="submit" value="INGRESAR A SU CUENTA">
    </form>
  </div>
</template>

<script>
export default {};
</script>



<style scoped>
.login {
  padding: 2rem;
}
.title {
  text-align: center;
  color:#D19A08;
  
}
.form {
  margin: 3rem auto;
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: 20%;
  min-width: 350px;
  max-width: 100%;
  border-color: #EDAD01;
  border-radius: 20px;
  padding: 40px;
  border: 2px solid;
  
}
.form-label {
  margin-top: 2rem;
  color:black;
  margin-bottom: 0.5rem;
  &:first-of-type {
    margin-top: 0rem;
  }
}
.form-input {
  padding: 10px 15px;
  background: none;
  background-image: none;
  border: 1px solid black;
  color: black;
  &:focus {
    outline: 0;
    border-color: #1ab188;
  }
}
.form-submit {

  border: none;
  color:black;
  margin-top: 3rem;
  padding: 1rem 0;
  cursor: pointer;
  
}
</style>

