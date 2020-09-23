<template>
  <div id="pc-menu">
    <div class="wrapper">
      <nav>
        <ul>
          <li><a href="./top.html">HOME</a></li>
          <li class="page_item "><a href="#">メニューA</a></li>
          <li class="page_item "><a href="#">メニューB</a></li>
          <li class="page_item "><a href="#">メニューC</a></li>
        </ul>
      </nav>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue, Prop, Watch } from "vue-property-decorator";
import Breadcrumb from "@/components/Breadcrumb.vue";

@Component({
  components: {
    Breadcrumb
  }
})
export default class ContentHeader extends Vue {
  head(): any {
    return {
      title: this.current.title
    };
  }

  @Prop({
    default: {
      url: "",
      title: ""
    }
  })
  current!: any;

  @Prop()
  breadcrumbList?: any[];
}
</script>
