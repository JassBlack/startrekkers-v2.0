<template>
  <header class="header-container  container">
    <div class="header-logo">
      <img src="../assets/images/tree.png" height="50" width="50" alt="">
    </div>
    <div class="header-nav">
      <ul class="header-nav__list">
        <li class="header-nav__item">MusicShare</li>
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
  align-items: center;
}

.header-logo {
  width: 70px;
}

.header-logo img{
  width: 100%;
  height: auto;
}

.header-nav__list {
  list-style: none;
  display: flex;
  width: 500px;
  justify-content: space-between;
  padding-left: 30px;
  box-sizing: border-box;
}

.header-nav__item {
  font-size: 22px;
  color: black;
  letter-spacing: .11em;
  font-weight: 300;
}
</style>
