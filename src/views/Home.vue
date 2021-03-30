<template>
  <div>
    <b-container class="d-flex align-items-center justify-content-center home">
      <b-row class="row">
        <b-col>
          <b-card bg-variant="dark" text-variant="white" title="Card Title">
            <b-card-text>
              With supporting text below as a natural lead-in to additional content.
            </b-card-text>
            <b-button href="#" variant="primary">Go somewhere</b-button>
          </b-card>
        </b-col>
      </b-row>
    </b-container>
    <Menu />
  </div>
</template>


<script>
import Menu from '@/components/Menu'
export default {
  name: 'Home',
  data(){
    return{
      bg: "#16a085" 
    }
  },
  components: {
    Menu
  }
}
</script>
 <style>
 #app {
  /* background: rgb(46,68,105);
  background: radial-gradient(circle at 0 100%,#6585b0,#2e4469); */
  background-color: #f6f7f9;
  color: #fff;
 }
 </style>