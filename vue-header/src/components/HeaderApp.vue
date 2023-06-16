<template>
  <header>
    <div class="nav">

        <NavLink v-for="link in links" 
        :navElement = "link" 
        />

    </div>
  </header>
</template>
<script>
import NavLink from './NavLink.vue';
export default {
  name : 'HeaderApp',

  components : {
    NavLink
  },



  data() {
    return {

      links : [
        {
                text : 'Questo',
            },

            {
                text : 'Questo',
            },

            {
                text : 'Questo',
            },

            {
                text : 'Questo',
            },

            {
                text : 'Questo',
            },
            
            {
                text : 'Questo'
            },
        ]
    }
  },
}
</script>

<style lang="scss">

  ul{
    display: flex;
  }

  li{
    display: flex;
    font-size: 2rem;
    margin: 0 10px;
    text-align: center;
    width: 100px;
    border: 5px solid violet;
  }


  .nav {
    display: flex;
  }
</style>