<template>
<div id="app">
   <nav>
    <div class="nav-wrapper">
      <a href="#" class="brand-logo" style="padding-left: 1rem;">Whom is Japanese</a>
      <ul id="nav-mobile" class="right hide-on-med-and-down">
          <router-link to="/tokugawa" tag="li"><a>Tokugawa</a></router-link>
      </ul>
    </div>
  </nav>
  <router-view/>
</div>
</template>

<style lang="scss">
#nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
    body {
        background: #333;
    }
</style>
