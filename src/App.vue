<template>
  <div>
    <md-card>
      <md-card-header>
        <div class="md-title">Vue JS Data Communication Example</div>      
      </md-card-header>
      <md-card-content>     
        
          
        <parent />

      </md-card-content>
    </md-card>
  </div>
</template>

<script>
  
import Parent from './components/data-communication/Parent.vue'
export default {
    name: 'app',
    components: {          
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
