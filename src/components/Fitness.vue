<template>
  <div id="fitness">
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
    name: 'fitness',
    data: function data(){
      return {
        items : [
          {
            id:'item01',
            description: 'Finish the year with 75 kg and less than 10% BF',
            status: false
          },{
            id:'item02',
            description: 'Run 600 km',
            status: false
          },{
            id:'item03',
            description: 'Try for 3 months a Ketogenic diet',
            status: false
          },{
            id:'item04',
            description: 'Bench press: 70 kg, Leg press: 150 kg and Squat: 60 kg',
            status: false
          },{
            id:'item05',
            description: "Don't drink soda for a year",
            status: false
          },{
            id:'item06',
            description: "Fix my posture",
            status: false
          },{
            id:'item07',
            description: "See the doctor more often",
            status: false
          },{
            id:'item08',
            description: "Sleep at least 6h/day for a year",
            status: false
          }
        ]
      }
    }
  }
</script>