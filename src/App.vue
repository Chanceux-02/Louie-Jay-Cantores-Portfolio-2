<template>
  <Header/>
  <About/>
  <Exp/>
  <Edu/>
  <Skills/>
  <Port/>
  <Cont/>
</template>

<script>

import Header from "./components/HeaderComponent.vue";
import About from "./components/AboutComponent.vue";
import Exp from "./components/ExpComponent.vue";
import Edu from "./components/EducationComponent.vue";
import Skills from "./components/SkillsComponent.vue";
import Port from "./components/PortComponent.vue";
import Cont from "./components/ContactComponent.vue";

export default {
  name: 'App',
  components: { 
    Header,
    About,
    Exp,
    Edu,
    Port,
    Cont,
    Skills,
    }
}
</script>

<style>
#app {
  font-family: "Poppins", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

</style>
