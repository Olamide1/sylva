<template>
  <div>
    <nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a class="navbar-item" href="https://bulma.io">
      <img src="https://bulma.io/images/bulma-logo.png" width="112" height="28">
    </a>

    <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>

  <div id="navbarBasicExample" class="navbar-menu">
    <div class="navbar-start">
      <a class="navbar-item">
        Home
      </a>

      <a class="navbar-item">
        Documentation
      </a>

      <div class="navbar-item has-dropdown is-hoverable">
        <a class="navbar-link">
          More
        </a>

        <div class="navbar-dropdown">
          <a class="navbar-item">
            About
          </a>
          <a class="navbar-item">
            Jobs
          </a>
          <a class="navbar-item">
            Contact
          </a>
          <hr class="navbar-divider">
          <a class="navbar-item">
            Report an issue
          </a>
        </div>
      </div>
    </div>

    <div class="navbar-end">
      <div class="navbar-item">
          FAQs
      </div>
    <div class="navbar-item">
            <a class="button">Get notified</a>
      </div>   
  
  </div>
  </div>
</nav>


<section class="hero is-large">
  <div class="hero-body">
    <p class="title is-size-1">
Saving for the Future. A Gig at a Time.
    </p>
    <p class="subtitle">
Sylva is a retirement savings account for gig workers/freelancers/entrepreneurs/bloggers/artists/online influencers minus all the paperwork. </p>
<a class="button are-small block">Get notified</a>

 </div>
</section>
<br>
<div class="block container">
  <p class="subtitle">
    <strong>    Sylva is built around 3 principles.
</strong>
</p>
  <div class="tile is-ancestor">
  <div class="tile is-4 is-vertical is-parent">
    <div class="tile is-child box">
      <p class="title">1.</p>
      <p> Make it easy for anyone who wants to save for their future in assets with better returns.</p>
    </div>
    <div class="tile is-child box">
      <p class="title">2.</p>
      <p>Help people figure out where their money is going.</p>
    </div>
  </div>
  <div class="tile is-parent">
    <div class="tile is-child box">
      <p class="title">3. </p>
      <p>Easily claim your retirement benefits without unneccsary paperwork.</p>
    </div>
  </div>
</div>
</div>


  <section class="section is-medium">
  <h1 class="title" id="second-title">The result?</h1>
  <h2 class="subtitle" id="subtitle">
    A powerful platform for people who want to retire at the age of  <strong id="subtitle">40</strong>, or more.
  </h2>
</section>


<footer class="footer">
  <div class="content has-text-centered">
    <p>
      <strong>Sylva</strong> by <a href="https://jgthms.com">Placeholder Ltd</a>.
    </p>
  </div>
</footer>
  </div>
</template>

<script>
document.addEventListener('DOMContentLoaded', () => {

  // Get all "navbar-burger" elements
  const $navbarBurgers = Array.prototype.slice.call(document.querySelectorAll('.navbar-burger'), 0);

  // Check if there are any navbar burgers
  if ($navbarBurgers.length > 0) {

    // Add a click event on each of them
    $navbarBurgers.forEach( el => {
      el.addEventListener('click', () => {

        // Get the target from the "data-target" attribute
        const target = el.dataset.target;
        const $target = document.getElementById(target);

        // Toggle the "is-active" class on both the "navbar-burger" and the "navbar-menu"
        el.classList.toggle('is-active');
        $target.classList.toggle('is-active');

      });
    });
  }

});
export default {
  name: 'Home',
  components: {
   
  }
}
</script>
<style scoped>
.hero{
  color: #374140 !important;
  background: #D9CB9E !important;
}
.section{
  background: #374140;
  color: #BDC3C7;
}
#second-title, #subtitle {
  color: #BDC3C7;
}
.footer{
  background: #BDC3C7 !important;
  color: white;
}

</style>