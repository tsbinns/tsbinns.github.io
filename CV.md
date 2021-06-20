---
title: "Curriculum Vitae"
layout: page
---

<a id="Top" class="section-ID"></a>

View the CV as a pdf <a href="/assets/documents/tsbinns-CV.pdf" target="_blank">here. &nbsp;<i class="fas fa-file-pdf"></i></a>

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
<!-- Main -->
<h1 style="padding-bottom: 0; margin-bottom: 0"><a id="Education" class="section-ID">Education</a></h1>
<div>
  <h3>
    09/2016 - 06/2021<br>
    University of Aberdeen<br>
    M.Sci. (Hons) Neuroscience with Psychology with Industrial Placement, First-Class Honours
  </h3>
  <p style="margin-left: 20px;">
    <b>Industrial Placement (Master's) thesis:</b><br>
    “Investigating neural precursors of self-initiated action using machine learning techniques”. First-Class.<br>
    Placement at the Bernstein Center for Computational Neuroscience, Berlin.<br>
    Supervisors: Dr. Matthias Schultze-Kraft and Prof. John-Dylan Haynes.<br>
  </p>
  <p style="margin-left: 20px;">
    <b>Honours (Bachelor's) thesis:</b><br>
    “Investigating the neuromodulation of striatal activity <i>in silico</i>”. First-Class.<br>
    Supervisor: Dr. Antonio Gonzalez.<br>
  </p>
</div>
<!-- Expandable -->
<div style="padding-top: 10px;">
  <button type="button" class="collapsible">View Additional Education</button>
  <div class="content">
      <h3>
        07/2020<br>
        Neuromatch Academy
      </h3>
      <p style="margin-left: 20px;">
        A three week highly intensive online summer school covering modelling, statistics, and machine learning, focusing on traditional and emerging tools of computational neuroscience, with extensive group work and Python programming.
      </p>
  </div>
</div>


<!-- Experience -->
<hr>
<h1><a id="Experience" class="section-ID">Experience</a></h1>


<!-- Publications -->
<hr>
<h1><a id="Publications" class="section-ID">Selected Publications</a></h1>

<p style="margin-bottom: 30px;">For the full list of publications, <a href="/publications" target="_blank">click here.</a></p>

<p>Schultze-Kraft, M., Jonany, V., <mark><b>Binns, T.S.</b></mark>, Soch, J., Blankertz, B. and Haynes, J.D., 2021. Suppress me if you can: neurofeedback of the readiness potential. <i>eNeuro</i>, <i>8</i>(2). <a href="https://www.doi.org/10.1523/eneuro.0425-20.2020" target="_blank">doi.org/10.1523/eneuro.0425-20.2020. <i class="fas fa-link"></i></a></p>
<button type="button" class="collapsible">View Description</button>
<div class="content">
    <p>
      Voluntary movements are usually preceded by a slow, negative-going brain signal over motor areas, the so-called readiness potential (RP). To date, the exact nature and causal role of the RP in movement preparation have remained heavily debated. Although the RP is influenced by several motorical and cognitive factors, it has remained unclear whether people can learn to exert mental control over their RP, for example, by deliberately suppressing it. If people were able to initiate spontaneous movements without eliciting an RP, this would challenge the idea that the RP is a necessary stage of the causal chain leading up to a voluntary movement. We tested the ability of participants to control the magnitude of their RP in a neurofeedback experiment. Participants performed self-initiated movements, and after every movement, they were provided with immediate feedback about the magnitude of their RP. They were asked to find a strategy to perform voluntary movements such that the RPs were as small as possible. We found no evidence that participants were able to to willfully modulate or suppress their RPs while still eliciting voluntary movements. This suggests that the RP might be an involuntary component of voluntary action over which people cannot exert conscious control.
    </p>
</div>

<p><mark><b>Binns, T.S.</b></mark>, 2020. Has neuroscience disproven free will?. <i>BNA Bulletin</i>, 1 August, p. 20. &nbsp;<a href="\assets\documents\BNA_article.pdf" target="_blank"><i class="fas fa-file-pdf"></i></a></p>
<button type="button" class="collapsible">View Description</button>
<div class="content">
    <p>
      A short review article examining whether research into the readiness potential, a neural marker of upcoming movement, has disproven free will. Published in the British Neuroscience Association's summer 2020 Bulletin.
    </p>
</div>


<!-- Funding -->
<hr>
<h1><a id="Funding" class="section-ID">Funding</a></h1>

<div>
  <p style="margin-bottom: 0;"><b>2019 - 2020</b></p>
  <p style="margin-left: 20px; margin-top: 0;">
    <b><i>Investigating choice-predictive brain signals using EEG-based brain-computer interfaces.</i> &euro;5,000.</b><br>
    Erasmus+ Traineeship grant, British Council.
  </p>
  <p style="margin-bottom: 0;"><b>2018</b></p>
  <p style="margin-left: 20px; margin-top: 0;">
    <b><i>Free Will and Neural Activity in Consequential Action.</i> &pound;2,000.</b><br>
    Biomedical Vacation Scholarship, Wellcome Trust.
  </p>
</div>


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
