<nav class="navbar navbar-expand-md navbar-light fixed-top bg-light">

  <!-- Brand -->
  <a class="navbar-brand" href="{{site.baseurl}}/">
    <img src="{{site.baseurl}}/assets/img/logo-homelife.gif">
    Indra MX
  </a>

  <!-- Toggle Expansion -->
  <button
    class="navbar-toggler"
    type="button"
    data-toggle="collapse"
    data-target="#navbar"
    aria-controls="navbar"
    aria-expanded="false"
    aria-label="Toggle navigation"
  >
    <span class="navbar-toggler-icon"></span>
  </button>

  <!--  Menu -->
  <div class="collapse navbar-collapse" id="navbar">
    <div class="navbar-nav ml-auto text-center text-md-left">
      <a
        class="
          nav-item nav-link
          {% if '/' == page.url %}active{% endif %}
        "
        href="{{site.baseurl}}/"
      >
        Home
      </a>
      <a
        class="
          nav-item nav-link
          {% if '/search' == page.url %}active{% endif %}
        "
        href="{{site.baseurl}}/search"
      >
        Search
      </a>
      <a
        class="
          nav-item nav-link
          {% if '/contact' == page.url %}active{% endif %}
        "
        href="{{site.baseurl}}/contact"
      >
        Contact
      </a>
      <a
        class="
          nav-item nav-link
          {% if '/testimonials' == page.url %}active{% endif %}
        "
        href="{{site.baseurl}}/testimonials"
      >
        Testimonials
      </a>
    </div>
  </div>
</nav>
