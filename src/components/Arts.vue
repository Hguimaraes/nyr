<template>
  <div id="arts">
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
    name: 'arts',
    data: function data(){
      return {
        items : [
          {
            id:'item01',
            description: 'Learn the basics about photography',
            status: false
          },{
            id:'item02',
            description: 'Learn how to play a musical instrument',
            status: false
          },{
            id:'item03',
            description: "Complete the 'Modern Art & Ideas' MOOC",
            status: false
          }
        ]
      }
    }
  }
</script>