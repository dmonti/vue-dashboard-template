<template>
  <div id="app">
    <core-navbar />
    <div class="container-fluid">
      <div class="row">
        <core-sidebar />
        <core-main />
      </div>
    </div>
  </div>
</template>

<script>
import feather from 'feather-icons'

export default {
  name: 'app',
  mounted: function () {
    feather.replace()
  }
}
</script>
<style lang="scss">
@import 'styles/index.scss';

.bd-placeholder-img {
  font-size: 1.125rem;
  text-anchor: middle;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

@media (min-width: 768px) {
  .bd-placeholder-img-lg {
    font-size: 3.5rem;
  }
}
</style>