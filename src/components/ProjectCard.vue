<script lang="ts">
export default {
  props: ['project'],
};
</script>
<template>
  <div class="card bg-black text-start position-relative">
    <div class="card-body position-absolute top-0 start-0 p-0">
      <img :src="project.image" class="card-img-top prj-img position-relative start-0" alt="...">
    </div>
    <div class="position-absolute end-0">
      <p class="aquamarine roboto">{{ project.featured }}</p>
      <h5 class="card-title pb-2">{{ project.title }}</h5>
      <div class="prj-info">
        <p class="card-text roboto bg-dark prj-overview">{{ project.description }}</p>
        <p class="grey">{{ project.technologies }}</p>
        <span>
          <a :href="project.github" target="_blank"><img src="./assets/git_icon.png" class="icon"></a>
          <a :href="project.link" target="_blank"><img src="./assets/hyperlink_icon.png" class="icon2"></a>
        </span>
      </div>
    </div>
  </div>
</template>


