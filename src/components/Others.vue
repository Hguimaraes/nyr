<template>
  <div id="others">
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
    name: 'others',
    data: function data(){
      return {
        items : [
          {
            id:'item01',
            description: "Learn all about a country that I've always been interested in",
            status: false
          },{
            id:'item02',
            description: 'Learn the basics of Meditation',
            status: false
          },{
            id:'item03',
            description: 'Learn a magic trick',
            status: false
          },{
            id:'item04',
            description: 'Learn how to read body language',
            status: false
          },{
            id:'item05',
            description: 'Standing up for a social cause that I believe in',
            status: false
          },{
            id:'item06',
            description: 'Watching an iconic TV show you never saw',
            status: false
          },{
            id:'item07',
            description: 'Save R$2500,00',
            status: true
          },{
            id:'item08',
            description: 'Travel more',
            status: true
          }
        ]
      }
    }
  }
</script>