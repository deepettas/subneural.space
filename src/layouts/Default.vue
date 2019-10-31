<template>
  <div class="layout">
    <header class="header">
      <g-image src="~/assets/Logo_one.png" fit="contain"  class="logo_image"/>

      <strong>
        <g-link to="/">{{ $static.metadata.siteName }}</g-link>
      </strong>
      
    </header>
    <slot/>
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style>
body {
  font-family: -apple-system,system-ui,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif;
  margin:0;
  padding:0;
  line-height: 1.5;
  background: #fff;

}

.layout {
  max-width: 760px;
  margin: 0 auto;
  padding-left: 20px;
  padding-right: 20px;
  
}

.header {
  margin: 0px 0px;
  padding-left: 10px;
  padding-right: 10px;
  padding-top: 49px;
  justify-content: space-between;

  
}

.nav__link {
  margin-left: 20px;
}
.logo_image{
  width:42px;
  height: auto
}
</style>
