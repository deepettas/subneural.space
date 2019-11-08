<template>
  <Layout :show-logo="true">
    Author intro
    <Author :show-title="true" />
    
    <!-- List posts -->
    <!-- <div class="posts">
      <PostCard v-for="edge in $page.posts.edges" :key="edge.node.id" :post="edge.node"/>
    </div> -->
    

    <g-link class="entries_link" :to="/entries/">Enter the space</g-link>

  </Layout>
</template>