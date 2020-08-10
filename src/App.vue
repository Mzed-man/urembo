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
      <button class="button violet">
        Button ui
      </button>
    </div>

    <form action="" class="form">
      <h1 class="title">
        Form Title
      </h1>
      <div class="field">
        <label for="">
          Label Name
        </label>
        <input type="text" name="" id="">
      </div>
      <div class="field">
        <label for="">
          Text area label
        </label>
        <textarea name="" id="" cols="30" rows="10"></textarea>
      </div>

      <div class="fields">

        <div class="field">
          <label for="">
            input 1
          </label>
          <input type="text">
        </div>

        <div class="field">
          <label for="">
            Input 2
          </label>
          <input type="text">
        </div>

        <div class="field">
          <label for="">
            Input 3
          </label>
          <input type="text">
        </div>

      </div>

    </form>

    <div class="list line wrap vertical">
      <div class="list-item vertical">
        <div class="ico">
          <img src="./assets/logo.png" alt="">
        </div>
        <div class="text">
          Vita est illis semper in fuga uxoresque mercenariae conductae ad tempus ex pacto atque, ut sit species matrimonii, dotis nomine futura coniunx hastam et tabernaculum offert marito, post statum diem si id elegerit discessura, et incredibile est quo ardore apud eos in venerem uterque solvitur sexus.
        </div>
        <div class="button">
          <button class="button primary">
            Navigate
          </button>
        </div>
      </div>
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
