<template>
  <div id="app">
   <Header />
   <b-container fluid>
     <b-row class="text-center">
       <b-col cols="2" class="NavBar">
         <RightNav/>
       </b-col>
       <b-col cols="7" class="middleNav">
         <div class="middleIn">
           <MiddleNav/>
           
  <Dashboard />
         </div>
       </b-col>
       <b-col cols="3">
         <div class="leftDiv">
           <LeftSide/>
         </div>
       </b-col>
      </b-row>
  </b-container>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import RightNav from './components/RightNav.vue'
import MiddleNav from './components/MiddleNav.vue'
import LeftSide from './components/LeftSide.vue'
import Dashboard from './components/Dashboard.vue'

export default {
  name: 'App',
  components: {
    Header,
    RightNav,
    MiddleNav,
    LeftSide,
    Dashboard
  }
}
</script>

<style>
.NavBar{
  height: fit-content;
  box-shadow: 5px 5px 5px rgb(218, 218, 218);
}
.middleNav{
  padding: 20px;
}
.middleIn{
  width: 100%;
  height: auto;
  background-color: #bed8ff47;
  border-radius: 20px;
  padding: 40px 30px;
}
.leftDiv{
  box-shadow: -5px 5px 5px rgb(218, 218, 218);
  text-align: left;
  padding: 20px;
}
</style>
