<template>
  <div >
    <div class="cat-page-title py-5">
      <div class="container">
        <h1>Repository list</h1>
      </div>
    </div>

    <container-repo-list></container-repo-list>
  </div>
</template>

<script>
import ContainerRepoList from '@/components/containers/ContainerRepoList.vue'

// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',

  components: {
    ContainerRepoList
  }
}
</script>
