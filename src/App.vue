<template>
  <div>
    <h1>{{ titulo }}</h1>

    <ul>
      <li v-for="foto of fotos">
        <img :src="foto.url" :alt="foto.titulo" />
      </li>
    </ul>
  </div>

</template>

<script>
export default {
data(){
  return{
    titulo: 'Alurapic',
    fotos: [
{
  url: 'https://abrilsuperinteressante.files.wordpress.com/2016/03/cachorro.png',
  titulo: 'cachorro'
},
{
  url: 'https://abrilsuperinteressante.files.wordpress.com/2016/03/cachorro.png',
  titulo: 'cachorro'
}
   ]
  }
}
};
</script>

<style>
</style>
