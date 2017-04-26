<template lang="html">
  <div class="">    
    <div class="cabecera">
      <p>{{email.asunto}}</p>
      <p>De: {{email.from}}</p>
      <p>Para: {{email.to}}</p>
    </div>
    <div class="contenido">
      <p>{{email.contenido}}</p>
    </div>
  </div>
</template>

<script>
export default {

  props: {
    email: ""
  }

}
</script>

<style lang="css" scoped>
  .cabecera{
    padding: 30px;
    border-radius: 30px;
    background-color: #F2F2F2;
  }

  .contenido{
    padding: 30px;
  }
</style>
