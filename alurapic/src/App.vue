<template>
  <div>
    <h1>{{titulo}}</h1>
    <ul>
      <li v-for="foto of fotos">
        <img :src="foto.url" :alt="foto.titulo"/>
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
          url: 'https://i.ytimg.com/vi/8qA4UOLnC5A/maxresdefault.jpg',
          titulo: 'Cachorro'
        },
        {
          url: 'https://i.ytimg.com/vi/8qA4UOLnC5A/maxresdefault.jpg',
          titulo: 'Cachorrão'
        }
      ]
    }      
  }
}
</script>

<style>

</style>
