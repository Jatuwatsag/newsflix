<template>
  <div>
    <img src="../../assets/banner.jpg" class="h-64 w-full object-cover" />
    <div class="w-full bg-home">
      <div class="container flex justify-between py-8">
        <div class="flex-1">
          <TopNews/>
        </div>
        <div class="flex-1">
          <div>Most View</div>
          <div>
            <div>Hello</div>
            <div>Hello</div>
            <div>Hello</div>
            <div>Hello</div>
            <div>Hello</div>
          </div>
        </div>
        <div class="flex-1">
          <div>Most Recent</div>
          <div>
            <div>Hello</div>
            <div>Hello</div>
            <div>Hello</div>
            <div>Hello</div>
            <div>Hello</div>
          </div>
        </div>
      </div>
    </div>
    <div class="w-full bg-inputhover">
      <div class="container">
        <PopularTags />
      </div>
    </div>
  </div>
</template>
<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import Chip from "@/components/Home/Chip.vue";
import PopularTags from "@/components/Home/PopularTags.vue";
import TopNews from "@/components/Home/TopNews.vue";
@Component({
  components: {
    Chip,
    PopularTags,
    TopNews
  }
})
export default class Index extends Vue {}
</script>
