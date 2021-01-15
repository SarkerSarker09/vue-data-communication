<template>
  <div>
    <md-card>
      <md-card-header>
        <div class="md-title">Material Design With Vue.js Demo</div>      
      </md-card-header>
      <md-card-content>     
        
             <sample-table /> 
        <sample/>
        <parent />

      </md-card-content>
    </md-card>
  </div>
</template>

<script>
  
import Sample from './components/Sample.vue'
import SampleTable from './components/SampleTable.vue'
import Parent from './components/data-communication/Parent.vue'

  export default {
    name: 'app',
    components: {          
        Sample,
        SampleTable,
        Parent,
    }    
  }
</script>

<style>
  #app {
    margin-top: 60px;
    margin-left: 30px;
    margin-right: 30px;
  }
</style>
