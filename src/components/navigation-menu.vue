<template>
  <div>
    <div class="navDrinks">
      <NavAlkoDrinks 
        
      />
      <NavSoftDrinks />
      <NavCoctails />
    </div>
  </div>
</template>

<script>
import NavAlkoDrinks from "./nav-alcoholic-drinks.vue";
import NavSoftDrinks from "./nav-soft-drinks.vue";
import NavCoctails from "./nav-cocktails-drinks.vue";


export default {
  components: {
    NavAlkoDrinks,
    NavSoftDrinks,
    NavCoctails,
  },

  methods: {
    
  }
}
</script>

<style>
.navDrinks {
  display: flex;
  justify-content: space-around;
  padding-left: 0;
  font-size: 24px;
  padding-bottom: 20px;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
  list-style: none;
}

.beverages {
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
  font-size: 24px;
  background-color: green;
  border: 3px solid black;
  border-radius: 30px;
  padding: 10px;
  cursor: pointer;
  text-decoration: none;
  color: black;
}

.general-style {
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
  font-size: 24px;
  /* text-align: center; */
  list-style: none;
  padding: 0;
}
</style>