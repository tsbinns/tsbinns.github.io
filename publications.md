---
title: "Publications"
layout: page
sitemap:
  lastmod: 2021-06-20
  exclude: 'no'
---
<a id="Top" class="section-ID"></a>

<!-- Google Scholar link -->
<i class="fab fa-google"></i> &nbsp; My Google Scholar profile: <a href="https://scholar.google.co.uk/citations?user=S8yDxUEAAAAJ">Thomas Samuel Binns</a>


<!-- Topbar for navigation of publications by year -->
<div class="dropdown">
  <button onclick="toggle_show()" class="dropdown_button"><i class="fas fa-bars"></i>&nbsp;&nbsp;Sections</button>
  <div id="dropdown_menu" class="dropdown_content">
    <a href="#Top">Top</a>
    <a href="#2021">2021</a>
    <a href="#2020">2020</a>
  </div>
</div>


<!-- Publication list -->
<h1><a id="2021" class="section-ID">2021</a></h1>

<ul>
    <li>Schultze-Kraft, M., Jonany, V., <mark><b>Binns, T.S.</b></mark>, Soch, J., Blankertz, B. and Haynes, J.D., 2021. Suppress me if you can: neurofeedback of the readiness potential. <i>eNeuro</i>, <i>8</i>(2). <a href="https://www.doi.org/10.1523/eneuro.0425-20.2020">doi.org/10.1523/eneuro.0425-20.2020.</a></li>
    <button type="button" class="collapsible">View Description</button>
    <div class="collapsible_content">
        <p>
          Voluntary movements are usually preceded by a slow, negative-going brain signal over motor areas, the so-called readiness potential (RP). To date, the exact nature and causal role of the RP in movement preparation have remained heavily debated. Although the RP is influenced by several motorical and cognitive factors, it has remained unclear whether people can learn to exert mental control over their RP, for example, by deliberately suppressing it. If people were able to initiate spontaneous movements without eliciting an RP, this would challenge the idea that the RP is a necessary stage of the causal chain leading up to a voluntary movement.
          We tested the ability of participants to control the magnitude of their RP in a neurofeedback experiment. Participants performed self-initiated movements, and after every movement, they were provided with immediate feedback about the magnitude of their RP. They were asked to find a strategy to perform voluntary movements such that the RPs were as small as possible. We found no evidence that participants were able to to willfully modulate or suppress their RPs while still eliciting voluntary movements. This suggests that the RP might be an involuntary component of voluntary action over which people cannot exert conscious control.
        </p>
    </div>
</ul>

<hr>
<h1><a id="2020" class="section-ID">2020</a></h1>

<ul>
    <li><mark><b>Binns, T.S.</b></mark>, 2020. Has neuroscience disproven free will?. <i>BNA Bulletin</i>, 1 August, p. 20. &nbsp;<a href="https://www.bna.org.uk/mediacentre/news/has-neuroscience-disproven-free-will/"><i class="fas fa-link"></i></a> &nbsp;<a href="/assets/documents/BNA_Article.pdf"><i class="fas fa-file-pdf"></i></a></li>
    <button type="button" class="collapsible">View Description</button>
    <div class="collapsible_content">
        <p>
          A short review article examining whether research into the readiness potential, a neural marker of upcoming movement, has disproven free will. Published in the British Neuroscience Association's summer 2020 Bulletin.
        </p>
    </div>
</ul>


<script>

  /* Makes collapsibles work */
  var coll = document.getElementsByClassName("collapsible");
  var i;
  for (i = 0; i < coll.length; i++) {
    coll[i].addEventListener("click", function() {
      this.classList.toggle("collapsible_active");
      var coll_content = this.nextElementSibling;
      if (coll_content.style.maxHeight){
        coll_content.style.maxHeight = null;
      } else {
        coll_content.style.maxHeight = coll_content.scrollHeight + "px";
      }
    });
  }

  /* Makes dropdowns work */
  /* When the user clicks on the button,
  toggle between hiding and showing the dropdown content */
  function toggle_show() {
    document.getElementById("dropdown_menu").classList.toggle("dropdown_show");
  }
  // Close the dropdown menu if the user clicks outside of it
  window.onclick = function(event) {
    if (!event.target.matches('.dropdown_button')) {
      var dropdowns = document.getElementsByClassName("dropdown_content");
      var j;
      for (j = 0; j < dropdowns.length; j++) {
        var openDropdown = dropdowns[j];
        if (openDropdown.classList.contains('dropdown_show')) {
          openDropdown.classList.remove('dropdown_show');
        }
      }
    }
  }

  // Applies offset to section links
  function offsetAnchor() {
    if (location.hash.length !== 0) {
      window.scrollTo(window.scrollX, window.scrollY - 100);
    }
  }
  // Captures click events of all <a> elements with href starting with #
  $(document).on('click', 'a[href^="#"]', function(event) {
    // Click events are captured before hashchanges. Timeout
    // causes offsetAnchor to be called after the page jump.
    window.setTimeout(function() {
      offsetAnchor();
    }, 0);
  });
  // Set the offset when entering page with hash present in the url
  window.setTimeout(offsetAnchor, 0);

</script>