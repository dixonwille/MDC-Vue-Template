<template>
  <div id="app">
    <header class="mdc-toolbar mdc-toolbar--fixed">
      <div class="mdc-toolbar__row">
        <section class="mdc-toolbar__section mdc-toolbar__section--align-start">
          <span class="mdc-toolbar__title">MDC Vue JS Template</span>
        </section>
      </div>
    </header>
    <main class="mdc-toolbar-fixed-adjust">
      <router-view></router-view>
    </main>
  </div>
</template>

<script lang="babel">
import { MDCToolbar } from '@material/toolbar';

export default {
  name: 'app',
  mounted: function () {
    const toolbar = new MDCToolbar(document.querySelector('.mdc-toolbar'));
    toolbar.fixedAdjustElement = document.querySelector('.mdc-toolbar-fixed-adjust');
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import '@material/toolbar/mdc-toolbar';

.mdc-toolbar__title{
  background: no-repeat 0/32px url(./assets/logo.png);
  padding: 2px 0 5px 50px;
}
</style>
