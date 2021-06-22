---
title: "About Me - Thomas Samuel Binns"
layout: page
---

<div class="alert">
  <p style="text-align: center;">
    For the intended experience,<br>
    please use Google Chrome.
  </p>
  <span class="closebtn" onclick="this.parentElement.style.display='none';">&times;</span>
</div>

<!-- Profile picture -->
<img width="25%" height="auto" style="float: left; margin-right: 20px;" src="/assets/images/ProfilePic.png">


<!-- Main website description/introduction -->
I am a neuroscientist from the UK interested in computational, cognitive, and translational neuroscience, with a particular interest in neuromodulation and brain-computer interfaces.

I have recently graduated with First-Class Honours in an M.Sci. Neuroscience with Psychology degree at the University of Aberdeen, UK. This included 12 months spent on placement at the Bernstein Center for Computational Neuroscience, Germany, investigating volition and decision-making using brain-computer interfaces in the lab of Prof. John-Dylan Haynes.

I am scheduled to begin my Ph.D. at the Einstein Center for Neurosciences Berlin, Germany, in October 2021.

Feel free to check out my [CV](/CV) and [publications](/publications), or contact me [here](/contact-links).


<script>
  // For animating the closing of the alert box //
  // Get all elements with class="closebtn"
  var close = document.getElementsByClassName("closebtn");
  var i;
  // Loop through all close buttons
  for (i = 0; i < close.length; i++) {
  // When someone clicks on a close button
  close[i].onclick = function(){
      // Get the parent of <span class="closebtn"> (<div class="alert">)
      var div = this.parentElement;
      // Set the opacity of div to 0 (transparent)
      div.style.opacity = "0";
      // Hide the div after 600ms (the same amount of milliseconds it takes to fade out)
      setTimeout(function(){ div.style.display = "none"; }, 600);
  }
  }
</script>