<template>
  <g-link class="about" to='/about/'>
                  about
  </g-link>
</template>


<style lang="scss">
.about {
    text-decoration: none;
    color: var(--body-color)!important;
    color: var(--body-color);
    cursor: pointer;
    padding-right: 1em;
    &:hover {
     opacity: .8
    }
      &:focus {
      outline: none;
    }
}
</style>