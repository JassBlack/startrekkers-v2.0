<template>
  <header class="header-container">
    <div class="header-logo">
      <img src="../assets/images/tree.png" height="50" width="50" alt="">
    </div>
    <div class="header-nav">
      <ul class="header-nav__list">
        <li class="header-nav__item">Music Share</li>
        <li class="header-nav__item">Listen</li>
        <li class="header-nav__item">Contacts</li>
      </ul>
    </div>  
  </header>
</template>

<script>
export default {
  name: 'HeaderNavigation',
  data () {
    return {

    }
  }
}
</script>

<style>

.header-container {
  display: flex;
  justify-content: space-between;
  flex-direction: row;
  background-color: rgba(255, 255, 255, 0.07);
  
}

.header-logo {
  width: 70px;
}

.header-logo img{
  width: 100%;
  height: auto;
}

</style>
