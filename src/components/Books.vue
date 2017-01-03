<template>
  <div id="books">
    <div class="container">
      <template v-for="item in items">
        <p>
          <input v-if="item.status" type="checkbox" id="item.id" checked="item.status" disabled="disabled" />
          <input v-else type="checkbox" id="item.id" disabled="disabled" />
          <label for="item.id">{{item.description}}</label>
        </p>
      </template>
    </div>
  </div>
</template>
<script>
  export default {
    name: 'books',
    data: function data(){
      return {
        items : [
          {
            id:'item01',
            description: 'Memórias póstumas de Brás Cubas - Machado de Assis',
            status: false
          },{
            id:'item02',
            description: 'Quincas Borba - Machado de Assis',
            status: false
          },{
            id:'item03',
            description: 'Final do Jogo - Julio Cortázar',
            status: false
          },{
            id:'item04',
            description: 'Memórias do Subsolo - Fiodor Dostoievski',
            status: false
          },{
            id:'item05',
            description: 'Ensaio sobre a cegueira - José Saramago',
            status: false
          },{
            id:'item06',
            description: 'The Subterraneans - Jack Kerouac',
            status: false
          },{
            id:'item07',
            description: 'Big Sur - Jack Kerouac',
            status: false
          },{
            id:'item08',
            description: 'Vision of Cody - Jack Kerouac',
            status: false
          },{
            id:'item09',
            description: 'First Third & Other Writings - Neal Cassady',
            status: false
          },{
            id:'item010',
            description: 'Howl - Allen Ginsberg',
            status: false
          },{
            id:'item011',
            description: 'Junky - William S. Burroughs',
            status: false
          },{
            id:'item012',
            description: 'Are We Smart Enough to Know How Smart Animals Are? - Frans de Waal',
            status: false
          },{
            id:'item013',
            description: 'Shoe Dog - Phil Knight',
            status: false
          },{
            id:'item014',
            description: 'In Search of Lost Time, Swann Way - Marcel Proust',
            status: false
          },{
            id:'item015',
            description: 'Elon Musk: Tesla, SpaceX, and the Quest for a Fantastic Future - Ashlee Vance',
            status: false
          }
        ]
      }
    }
  }
</script>