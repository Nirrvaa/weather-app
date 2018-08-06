<template>
  <div id="app">
    <div id="nav">
      <md-tabs md-sync-route>
        <md-tab id="tab-home" md-label="Home" to="home"></md-tab>
        <md-tab id="tab-about" md-label="Pages" to="about"></md-tab>
      </md-tabs>
    </div>
    <router-view/>
  </div>
</template>
