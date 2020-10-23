<template>
  <div class="container">
    <div class="grid">
        <b-container class="bv-example-row d-flex justify-content-center">
        <b-row>
            <b-col md="4" v-for="character in characters" :key="character.id" class="d-flex justify-content-center">
                <b-card
                    :title="character.name"
                    :img-src="character.src"
                    img-alt="Image"
                    img-top
                    tag="article"
                    style="max-width: 20rem;"
                    class="mb-5"
                    >
                </b-card>
            </b-col>
        </b-row>
        </b-container>
    </div>
  </div>
</template>

<script>
export default {
  name:'grid-component',
  props:{
    characterName:{
      type:String,
      required:true,
    },
    srcImg:{
      type:String,
      required:true,
    },
    id:{
      type:Number,
      required:true,
    }
  },
  data:function(){
    return {
      characters:[
        {id:1, name:'Morty', src:'https://rickandmortyapi.com/api/character/avatar/2.jpeg'},
        {id:2, name:'Rick',  src: 'https://rickandmortyapi.com/api/character/avatar/1.jpeg'},
        {id:3, name: 'Summer', src: 'https://rickandmortyapi.com/api/character/avatar/3.jpeg'},
        {id:4, name: 'Beth', src: 'https://rickandmortyapi.com/api/character/avatar/4.jpeg'},
        {id:5, name: 'Jerry', src: 'https://rickandmortyapi.com/api/character/avatar/5.jpeg'},
      ]
    }
  },
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.grid{
    margin-top:50px;
}
</style>