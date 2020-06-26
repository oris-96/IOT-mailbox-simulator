<template>
  <div class="u-margin-top">
   

<div class="container fluid ">
<b-container class="bv-example-row">
<b-row>
 <b-col>
  <Notification/>
     </b-col>
    <b-col >
  <ControlPanel/>
  <b-row> 
    <b-col sm="10">
    <LogPanel/>
    </b-col >
     </b-row>

    </b-col>
 </b-row>
</b-container>

</div>
  
  </div>
</template>

<script>

import ControlPanel from "./components/ControlPanel.vue";
import Notification from "./components/Notification.vue";
import LogPanel from "./components/LogPanel.vue";


export default {
  name: "App",
  components: {
    ControlPanel,
    Notification,
    LogPanel
  }
};
</script>

<style>

.u-margin-top{
  margin-top: 30px;
}

</style>
