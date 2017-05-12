<template>
  <div class="hello mdc-layout-grid__cell mdc-layout-grid__cell--span-12">
    <h1 class="mdc-typography--display1">{{ msg }}</h1>
    <div class="mdc-layout-grid">
      <div class="mdc-layout-grid__cell mdc-layout-grid__cell--span-6">
        <div class="mdc-card">
          <section class="mdc-card__primary">
            <h1 class="mdc-card__title mdc-card__title--large">Essential Links</h1>
          </section>
          <section class="mdc-card__supporting-text">
            <ul class="mdc-list">
              <li class="mdc-list-item"><a href="https://vuejs.org" target="_blank">Core Docs</a></li>
              <li class="mdc-list-item"><a href="https://forum.vuejs.org" target="_blank">Forum</a></li>
              <li class="mdc-list-item"><a href="https://gitter.im/vuejs/vue" target="_blank">Gitter Chat</a></li>
              <li class="mdc-list-item"><a href="https://twitter.com/vuejs" target="_blank">Twitter</a></li>
              <li class="mdc-list-item"><a href="http://vuejs-templates.github.io/webpack/" target="_blank">Docs for This Template</a></li>
            </ul>
          </section>
        </div>
      </div>
      <div class="mdc-list-grid__cell mdc-layout-grid__cell--span-6">
        <div class="mdc-card">
          <section class="mdc-card__primary">
            <h1 class="mdc-card__title mdc-card__title--large">Ecosystem</h1>
          </section>
          <section class="mdc-card__supporting-text">
            <ul class="mdc-list">
              <li class="mdc-list-item"><a href="http://router.vuejs.org/" target="_blank">vue-router</a></li>
              <li class="mdc-list-item"><a href="http://vuex.vuejs.org/" target="_blank">vuex</a></li>
              <li class="mdc-list-item"><a href="http://vue-loader.vuejs.org/" target="_blank">vue-loader</a></li>
              <li class="mdc-list-item"><a href="https://github.com/vuejs/awesome-vue" target="_blank">awesome-vue</a></li>
            </ul>
          </section>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">
@import '@material/list/mdc-list';
@import '@material/card/mdc-card';
</style>
