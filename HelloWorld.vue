<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
    Sejam bem vindos(as) a minha nova página
    </p>
    <h3>Modelos</h3>
    <ul>
      <li><a href="https://www.instagram.com/marciaferreirabolos/" target="_blank" rel="noopener">Referências</a></li>
    </ul>
    <h3>Faça seu pedido</h3>
    <ul>
      <li><a href="https://wa.me/5565999289914" target="_blank" rel="noopener">Orçamentos</a>
      </li>
    </ul>
    <h3>Contato</h3>
    <ul>
      <li><a href="https://wa.me/5565999289914" target="_blank" rel="noopener">Whatsapp</a></li>
      <li><a href="https://www.instagram.com/marciaferreirabolos/" target="_blank" rel="noopener">Instagram</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 30px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #dd8f99;
}
</style>
