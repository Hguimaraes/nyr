<template>
<div id="dashboard" align="middle">
  <div class="row valign-wrapper">
    <div id="card-small" class="card small hoverable valign col s4">
      <div class="card-image waves-effect waves-block waves-light">
        <img class="activator" src="imgs/books.svg">
      </div>
      <p></p>
      <div class="divider"></div>
      <div class="card-content">
        <span class="card-title activator grey-text text-darken-4">Books<i class="material-icons right">more_vert</i></span>
        <p><a href="#">Check this category</a></p>
      </div>
      <div class="card-reveal">
        <span class="card-title grey-text text-darken-4">Books<i class="material-icons right">close</i></span>
        <p>In this card you will find the list of books that I would like to read this year.</p>
      </div>
    </div>

    <div id="card-small" class="card small hoverable valign col s4">
      <div class="card-image waves-effect waves-block waves-light">
        <img class="activator" src="imgs/fitness.svg">
      </div>
      <p></p>
      <div class="divider"></div>
      <div class="card-content">
        <span class="card-title activator grey-text text-darken-4">Fitness<i class="material-icons right">more_vert</i></span>
        <p><a href="#">Check this category</a></p>
      </div>
      <div class="card-reveal">
        <span class="card-title grey-text text-darken-4">Fitness<i class="material-icons right">close</i></span>
        <p>Fitness goals of 2017. Strengh, weigth, body fat reduction and other goals.</p>
      </div>
    </div>

    <div id="card-small" class="card small hoverable valign col s4">
      <div class="card-image waves-effect waves-block waves-light">
        <img class="activator" src="imgs/arts.svg">
      </div>
      <p></p>
      <div class="divider"></div>
      <div class="card-content">
        <span class="card-title activator grey-text text-darken-4">Arts<i class="material-icons right">more_vert</i></span>
        <p><a href="#">Check this category</a></p>
      </div>
      <div class="card-reveal">
        <span class="card-title grey-text text-darken-4">Arts<i class="material-icons right">close</i></span>
        <p>Develop more "artistic" skills, such as photography and painting. Check out!</p>
      </div>
    </div>
  </div>
  <div class="row valign-wrapper">
    <div id="card-small" class="card small hoverable valign col s4">
      <div class="card-image waves-effect waves-block waves-light">
        <img class="activator" src="imgs/education.svg">
      </div>
      <p></p>
      <div class="divider"></div>
      <div class="card-content">
        <span class="card-title activator grey-text text-darken-4">Education<i class="material-icons right">more_vert</i></span>
        <p><a href="#">Check this category</a></p>
      </div>
      <div class="card-reveal">
        <span class="card-title grey-text text-darken-4">Education<i class="material-icons right">close</i></span>
        <p>Learning plan for 2017! From new cs skills (or improve) to Financial market 101.</p>
      </div>
    </div>

    <div id="card-small" class="card small hoverable valign col s4">
      <div class="card-image waves-effect waves-block waves-light">
        <img class="activator" src="imgs/experience.svg">
      </div>
      <p></p>
      <div class="divider"></div>
      <div class="card-content">
        <span class="card-title activator grey-text text-darken-4">Experience<i class="material-icons right">more_vert</i></span>
        <p><a href="#">Check this category</a></p>
      </div>
      <div class="card-reveal">
        <span class="card-title grey-text text-darken-4">Experience<i class="material-icons right">close</i></span>
        <p>Things that I want (and will) experience this year.</p>
      </div>
    </div>

    <div id="card-small" class="card small hoverable valign col s4">
      <div class="card-image waves-effect waves-block waves-light">
        <img class="activator" src="imgs/others.svg">
      </div>
      <p></p>
      <div class="divider"></div>
      <div class="card-content">
        <span class="card-title activator grey-text text-darken-4">Others<i class="material-icons right">more_vert</i></span>
        <p><a href="#">Check this category</a></p>
      </div>
      <div class="card-reveal">
        <span class="card-title grey-text text-darken-4">Others<i class="material-icons right">close</i></span>
        <p>Mixed content that doesn't fit so well on the other categories.</p>
      </div>
    </div>
  </div>
</div>
</template>

<script >
  
</script>

<style lang="sass">
  #card-small {
    width: 220px;
    height: 350px;
    margin: 15px;
  }

  #dashboard {
    margin: 0 auto;
    width: 85%;
    padding: 25px;
  }
</style>