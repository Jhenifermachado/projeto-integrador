<script>
export default {};
</script>
<template>
  <header id="header">
    <div class="logo">
      <img src="@/assets/logoo.png" />
    </div>
    <nav class="menu">
      <a>Início</a>
      <a>|</a>
      <a>Animais</a>
      <a>|</a>
      <a>Doações</a>
      <a>|</a>
      <a>Procurar</a>
    </nav>
  </header>
</template>
<style>
.menu {
  display: flex;
  margin-top: 30px;
  color: #beaee2;
  font-size: 1.2em;
  font-family: "Times New Roman", Times, serif;
}

.menu > a {
  padding-left: 20px;
}

.menu > a:hover {
  font-size: 1.25em;
}
</style>
