---
title: "About Me - Thomas Samuel Binns"
layout: page
---

<a id="Top" class="section-ID"></a>


<!-- Topbar for navigation of publications by year -->
<div class="scrollmenu">
  &nbsp;&nbsp;&nbsp;<b>Jump to:</b>
  <a href="#Top">Top</a>
  <a href="#Education">Education</a>
  <a href="#Experience">Experience</a>
  <a href="#Publications">Publications</a>
  <a href="#Funding">Funding</a>
  <a href="#Memberships">Memberships</a>
  <a href="#Skills">Skills</a>
  <a href="#Achievements-Interests">Achievements & Interests</a>
  <a href="#References">References&nbsp;&nbsp;</a>
</div>


<!-- Education -->
<h1><a id="Education" class="section-ID">Education</a></h1>

<div style="white-space: pre-line">
  <b>09/2016 - 06/2021 &emsp; University of Aberdeen</b>
  <b>M.Sci. (Hons) Neuroscience with Psychology with Industrial Placement</b>
  First-Class Honours
  <b>Industrial Placement (Master's) thesis -</b> “Investigating neural precursors of self-initiated action using machine learning techniques”. Placement at the Bernstein Center for Computational Neuroscience, Berlin. Supervisors: Dr. Matthias Schultze-Kraft and Prof. John-Dylan Haynes. First-Class.
  <b>Honours (Bachelor's) thesis -</b> "Investigating the neuromodulation of striatal activity <i>in silico</i>”. Supervisor: Dr. Antonio Gonzalez. First-Class.
</div>

<div style="white-space: pre-line">
  <b>07/2020 &emsp; Neuromatch Academy</b>
  A three week highly intensive online summer school covering modelling, statistics, and machine learning, focusing on traditional and emerging tools of computational neuroscience, with extensive group work and Python programming.
</div>


<!-- Experience -->
<hr>
<h1><a id="Experience" class="section-ID">Experience</a></h1>


<!-- Publications -->
<hr>
<h1><a id="Publications" class="section-ID">Publications</a></h1>


<!-- Funding -->
<hr>
<h1><a id="Funding" class="section-ID">Funding</a></h1>


<!-- Memberships -->
<hr>
<h1><a id="Memberships" class="section-ID">Memberships</a></h1>


<!-- Skills -->
<hr>
<h1><a id="Skills" class="section-ID">Skills</a></h1>


<!-- Achievements & Interests -->
<hr>
<h1><a id="Achievements-Interests" class="section-ID">Achievements & Interests</a></h1>


<!-- References -->
<hr>
<h1><a id="References" class="section-ID">References</a></h1>

Available on request. &nbsp; <a href="mailto:t.s.binns@outlook.com"><i class="fas fa-envelope"></i></a>


<script>
  
  /* Makes collapsibles work */
  var coll = document.getElementsByClassName("collapsible");
  var i;

  for (i = 0; i < coll.length; i++) {
    coll[i].addEventListener("click", function() {
      this.classList.toggle("active");
      var content = this.nextElementSibling;
      if (content.style.maxHeight){
        content.style.maxHeight = null;
      } else {
        content.style.maxHeight = content.scrollHeight + "px";
      }
    });
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
