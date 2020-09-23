<template>
  <header class="header">
    <div class="wrapper">
      <div class="header-logo"><a href="#">ブログタイトル</a></div>
      <div class="nav">
        <div class="search">
          <form role="search" method="get" action="#">
            <i class="fas fa-search search-icon"></i>
            <label>
              <input type="search" placeholder="検索..." value="" name="s">
            </label>
          </form>
        </div>
        <div class="menu-btn"><figure></figure><figure></figure><figure></figure></div>
        <div id="side-menu">
          <div class="side-menu-header">
            <div class="search">
              <form role="search" method="get" action="#">
                <i class="fas fa-search search-icon"></i>
                <label>
                  <input type="search" placeholder="検索..." value="" name="s">
                </label>
              </form>
            </div>
          </div>
          <nav>
            <ul>
              <li><a href="./top.html">HOME</a></li>
              <li><a href="#" >メニューA</a></li>
              <li><a href="#" >メニューB</a></li>
              <li><a href="#" >メニューC</a></li>
            </ul>
          </nav>
        </div>
        <div id="layer-panel"></div>
      </div>
    </div>
  </header>
</template>

<script lang="ts">
import { Component, Vue, Prop, Watch } from "vue-property-decorator";

@Component
export default class Header extends Vue {
  head(): any {
    return {
      bodyAttrs: {
        class: this.openSideMenu ? "sidebar-mini sidebar-collapse" : ""
      }
    };
  }

  openSideMenu = true;

  mounted(): void {
    // サイドメニューの開閉状態をクッキーから復元
    const re = new RegExp("sidebarToggleState" + "=([^;]+)");
    const value = re.exec(document.cookie);
    const toggleState = value !== null ? unescape(value[1]) : null;
    if (toggleState === "closed") {
      this.openSideMenu = false;
    }
  }

  // サイドメニューの開閉
  pushmenu(): void {
    const path = "/";
    if (this.openSideMenu) {
      document.cookie = "sidebarToggleState=closed; path=" + path + ";";
    } else {
      document.cookie = "sidebarToggleState=opened; path=" + path + ";";
    }
  }
}
</script>
