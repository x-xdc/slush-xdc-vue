<template>
  <h1><%= name %></h1>
  <p><%= description %></p>
  <router-view></router-view>
</template>

<script type="text/babel">
  import './assets/font/iconfont.css';

  export default {
    name: 'app'
  };
</script>
