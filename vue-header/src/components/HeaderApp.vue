<template>
  <header>
    <div>
      <ul>
        <li>

        <NavLink v-for="link in links" 
        :navElement = "link" 
        />
        </li>
      </ul>
    </div>
  </header>
</template>
<script>
import NavLink from './NavLink.vue';
export default {
  name : 'HeaderApp',

  component : {
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
    font-size: 2rem;
    margin: 0 10px;
    text-align: center;
    width: 100px;
    border: 5px solid violet;
  }
</style>