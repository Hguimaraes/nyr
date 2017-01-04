<template>
  <div id="education">
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
    name: 'education',
    data: function data(){
      return {
        items : [
          {
            id:'item01',
            description: 'Publish 2 papers',
            status: false
          },{
            id:'item02',
            description: 'Read 150 papers',
            status: false
          },{
            id:'item03',
            description: 'Study about cryptography and Cyber secutiry',
            status: false
          },{
            id:'item04',
            description: 'Study and use Docker',
            status: false
          },{
            id:'item05',
            description: 'Learn about Amazon webservices and how to use for Big data, Data Science and Deep Learning',
            status: false
          },{
            id:'item06',
            description: 'Learn Lua (Programming Language)',
            status: false
          },{
            id:'item07',
            description: 'Do more projects with C++ and Python',
            status: false
          },{
            id:'item08',
            description: 'More DIY proejcts using Arduino, Raspberry PI and/or Intel Galileo',
            status: false
          },{
            id:'item09',
            description: "Get the 'Cambridge English: Advanced (CAE)' certificate",
            status: false
          },{
            id:'item010',
            description: "Get the 'EMC Data Scientist Associate' certification",
            status: false
          },{
            id:'item011',
            description: 'Study about Buddhism',
            status: false
          },{
            id:'item012',
            description: 'Learn a new language',
            status: false
          },{
            id:'item013',
            description: 'Study the basics of Stock Market',
            status: false
          },{
            id:'item014',
            description: 'Write a killing resume',
            status: false
          },{
            id:'item015',
            description: 'Interview at one of the top 10 tech companies/startups',
            status: false
          },{
            id:'item016',
            description: "Study at least 30 minutes per day the courses that I'm taking at univerisity",
            status: false
          },{
            id:'item017',
            description: 'Apply for international master degrees opportunities',
            status: false
          },{
            id:'item018',
            description: 'Complete at leats 5 MOOCs',
            status: false
          },{
            id:'item019',
            description: 'Learn how to give a good presentation',
            status: false
          },{
            id:'item020',
            description: 'Learn about start a new business',
            status: false
          },{
            id:'item021',
            description: 'Learn how to defend myself',
            status: false
          },{
            id:'item022',
            description: 'Use task lists (or to-do lists) to follow deadlines',
            status: false
          }
        ]
      }
    }
  }
</script>