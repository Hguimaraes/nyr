<template>
  <div id="experience">
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
    name: 'experience',
    data: function data(){
      return {
        items : [
          {
            id:'item01',
            description: 'Stay sober for 3 months',
            status: false
          },{
            id:'item02',
            description: 'A concert with a band/artist that I really like but never saw',
            status: false
          },{
            id:'item03',
            description: "Go to a new bar or nightclub that I've always eyed",
            status: false
          },{
            id:'item04',
            description: 'Skydiving',
            status: false
          },{
            id:'item05',
            description: 'Blood donation',
            status: false
          },{
            id:'item06',
            description: 'Doing or saying one kind thing a day for an entire year',
            status: false
          },{
            id:'item07',
            description: "Voicing my opinion on something I've been holding in",
            status: false
          },{
            id:'item08',
            description: 'Rock Climbing',
            status: false
          },{
            id:'item09',
            description: 'Trekking and camping for more than 2 days',
            status: false
          },{
            id:'item010',
            description: 'Go to a beer tasting event',
            status: false
          },{
            id:'item011',
            description: "Give a talk about something that I know/I'm good at",
            status: false
          },{
            id:'item012',
            description: "Getting to know a random person's life story",
            status: false
          },{
            id:'item013',
            description: 'Stay 1 month without social media/apps',
            status: false
          },{
            id:'item014',
            description: 'Be vegan for 1 month',
            status: false
          },{
            id:'item015',
            description: 'Talk and understanding someone with a different political opinion than mine',
            status: false
          },{
            id:'item016',
            description: 'Go to meetups or maker spaces',
            status: true
          }
        ]
      }
    }
  }
</script>