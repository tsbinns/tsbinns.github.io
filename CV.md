---
title: "Curriculum Vitae"
layout: page
---

<a id="Top" class="section-ID"></a>

Download the CV as a pdf. <a href="/assets/documents/tsbinns-CV.pdf">&nbsp;<i class="fas fa-file-pdf"></i></a>

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
<h1 style="padding-bottom: 0; margin-bottom: 0"><a id="Education" class="section-ID">Education</a></h1>
<div>
  <p style="text-size:x-large">
    <b>09/2016 - 06/2021 &emsp; University of Aberdeen<br>
    M.Sci. (Hons) Neuroscience with Psychology with Industrial Placement</b><br>
    First-Class Honours
  </p>
  <p style="margin-left: 20px; text-size:larger">
    <b>Industrial Placement (Master's) thesis</b><br>
    “Investigating neural precursors of self-initiated action using machine learning techniques”. First-Class.<br>
    Placement at the Bernstein Center for Computational Neuroscience, Berlin.<br>
    Supervisors: Dr. Matthias Schultze-Kraft and Prof. John-Dylan Haynes.<br>
  </p>
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
