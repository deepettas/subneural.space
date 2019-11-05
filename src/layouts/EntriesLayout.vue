<template>
  <div class="layout">
    <header class="header">
        <g-image src="~/assets/Logo_one.png" class="logo_image"/>

        <div class="header-title"> Entries, yo </div>

      
      
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
  font-family: HelveticaNowDisplay-Light;
  src: url('../assets/fonts/HelveticaNowDisplay-Light.ttf');
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
}

.header-title { 
  padding-left: 27px;
  margin:0;
  display: inline-block;

}

.nav__link {
  
  margin-left: 20px;
}
.logo_image{
  width:42px;
  height: auto;
  box-sizing: border-box;
}
</style>
