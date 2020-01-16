<template>
  <div id="app" style="-webkit-app-region: drag" class="flex min-h-screen">
    <!--
    <div id="nav" class="clickable">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    -->
    <div class="w-56 bg-indigo-900 text-white border-r border-blue-900 fixed min-h-screen">
      This is the sidebar
    </div>
    <router-view/>
  </div>
</template>