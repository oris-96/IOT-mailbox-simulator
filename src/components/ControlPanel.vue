<template>
<div>
<b-list-group>
  <b-list-group-item>monitoring started</b-list-group-item>
   
  <b-list-group-item class="u-margin-right">
     
       <button class="btn btn-md btn-primary"> start monitoring</button>
      <button class="btn btn-md btn-warning"> stop monitoring</button>
      <button class="btn btn-md btn-danger">reset</button>
    
  </b-list-group-item>
</b-list-group>
</div>
    
</template>


<script>
export default {
    name: "ControlPanel",
    
}
</script>


<style lang="scss" scoped>

.u-margin-right{
     margin-right: 40px;
    &:not(last-child){
        margin-right: 40px;
    }
}

</style>