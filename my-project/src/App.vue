<template>
  <div>
    <HeaderE 
      @load-paginfo="showPagInfo" 
      @load-pagsobre="showPagSobre" 
      @load-pagcontato="showPagContato"
    />
    <PagContato v-if="showPagContatoComponent" />
    <PagInfo v-if="showPagInfoComponent" />
    <PagSobre v-if="showPagSobreComponent" />
    <UserStorage />
    <FooterObject />
    
    
    
  </div>
</template>

<script>
import HeaderE from './components/HeaderE.vue';
import UserStorage from "@/components/UserStorage.vue";
import FooterObject from "@/components/FooterObject.vue";
import PagInfo from './components/PagInfo.vue';
import PagSobre from './components/PagSobre.vue';
import PagContato from './components/PagContato.vue';

export default {
  name: 'App',
  components: {
    HeaderE,
    UserStorage,
    FooterObject,
    PagInfo,
    PagSobre,
    PagContato
  },
  data() {
    return {
      showPagInfoComponent: false,
      showPagSobreComponent: false,
      showPagContatoComponent: false
    };
  },
  methods: {
    showPagInfo() {
      this.showPagInfoComponent = true;
      this.showPagSobreComponent = false; // Garante que só um está visível
      this.showPagContatoComponent = false;
    },
    showPagSobre() {
      this.showPagInfoComponent = false; // Garante que só um está visível
      this.showPagSobreComponent = true;
      this.showPagContatoComponent = false;
    },
    showPagContato() {
      this.showPagInfoComponent = false;
      this.showPagSobreComponent = false;
      this.showPagContatoComponent = true;
    }
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
</style>
