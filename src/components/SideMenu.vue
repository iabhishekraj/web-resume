<template>
  <div id="sidebar">
    <ul>
      <li class="side-menu" v-scroll-to="'#extended-info'">
        <router-link to="/">
          <div class="menu-icon">
            <i class="fas fa-user"></i>
            <p class="menu-text">About</p>
          </div>
        </router-link>
      </li>
      <li class="side-menu" v-scroll-to="'#extended-info'">
        <router-link to="/profile">
          <div class="menu-icon">
            <i class="fas fa-id-badge"></i>
            <p class="menu-text">Profile</p>
          </div>
        </router-link>
      </li>
      <li class="side-menu" v-scroll-to="'#extended-info'">
        <router-link to="/projects">
          <div class="menu-icon">
            <i class="fas fa-tasks"></i>
            <p class="menu-text">Projects</p>
          </div>
        </router-link>
      </li>
      <li class="side-menu" v-scroll-to="'#extended-info'">
        <router-link to="/contact">
          <div class="menu-icon">
            <i class="fas fa-paper-plane"></i>
            <p class="menu-text">Contact</p>
          </div>
        </router-link>
      </li>
    </ul>
  </div>
</template>
<script>
export default {
  name: "SideMenu",
};
</script>
<style scoped>
</style>