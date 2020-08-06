<template>
  <div>

    <div class="nav big even secondary">
      <div class="logo">
        <img src="./assets/logo.png">
      </div>
      <div class="menu">
        <a href="http://" class="menu-item">Navigation 1</a>
        <a href="http://" class="menu-item">Navigation 2</a>
        <a href="http://" class="menu-item">Navigation 3</a>
        <a href="http://" class="menu-item">Navigation 4</a>
      </div>
    </div>

    <div class="notification success">
      <div class="content">
        <div class="icon">
          <img src="./assets/logo.png" alt="">
        </div>
        <div class="message">
          <h3 class="title" >Title for the message</h3>
          <p class="text">
            Message content, should be a short text to say briefly what is the matter
          </p>
        </div>
      </div>
      <div class="buttons">
        <button class="button">First option</button>
        <button class="button">Second option</button>
      </div>
    </div>

    <div>
      <button class="button yellow">
        Button ui
      </button>
    </div>

  </div>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">
  @import './styles/styles.scss';
</style>
