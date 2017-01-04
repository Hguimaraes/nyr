<template>
  <div>
    <nav class="nav-extended light-blue lighten-1">
      <div class="nav-wrapper">
        <a href="#" class="brand-logo center"><img class="responsive-img" id="logo" src="imgs/logo.png" /></a>
        <a href="#" data-activates="mobile-demo" class="button-collapse"><i class="material-icons">menu</i></a>
        <ul id="nav-mobile" class="right hide-on-med-and-down">
          <li><a href="badges.html">About</a></li>
          <li><a href="https://github.com/Hguimaraes/nyr">Github</a></li>
        </ul>
        <ul class="side-nav" id="mobile-demo">
          <li><a href="badges.html">About</a></li>
          <li><a href="https://github.com/Hguimaraes/nyr">Github</a></li>
        </ul>
        <ul class="tabs tabs-fixed-width tabs-transparent">
          <li class="tab"><a href="#arts">Arts</a></li>
          <li class="tab"><a href="#books">Books</a></li>
          <li class="tab"><a href="#education">Education</a></li>
          <li class="tab"><a class="activate" href="#dashboard">Dashboard</a></li>
          <li class="tab"><a href="#experience">Experience</a></li>
          <li class="tab"><a href="#fitness">Fitness & Health</a></li>
          <li class="tab"><a href="#others">Others</a></li>
        </ul>
      </div>
    </nav>
  </div>
</template>
<style lang="sass">
  .responsive-img{
    vertical-align: middle;
  }
</style>