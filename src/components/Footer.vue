<template>
  <footer class="footer">
    <div class="wrapper">
      <div class="footer-nav">
        <ul>
          <li><a href="./top.html" ><font-awesome-icon :icon="['fas','home']" /></a></li>
          <li><a href="#" class="js-overlay" data-panel="#sns-share-overlay"><font-awesome-icon :icon="['fas','share-alt']" /></a></li>
          <li><a href="#" class="js-open-menu"><font-awesome-icon :icon="['fas','bars']" /></a></li>
          <li><a href="#" class="js-scroll-top"><font-awesome-icon :icon="['fas','chevron-up']" /></a></li>
        </ul>
      </div>
      <section class="follow-links">
        <ul class="menu">
          <li><a href="#" >プライバシーポリシー</a></li>
          <li><a href="#" >お問い合わせ</a></li>
          <li><a href="#" >RSS</a></li>
        </ul>
      </section>
      <section class="copylight">© 2020 isystk's blog</section>
    </div>
  </footer>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component
export default class Footer extends Vue {}
</script>
