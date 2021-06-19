---
title: "Test"
layout: page
---

<input type="button" onclick="growDiv()" value="View Description" id="more-button">

<div class="grow-content" id='grow'>
  <div class='measuringWrapper'>
    <p>Here is some more text: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum vitae urna nulla. Vivamus a purus mi. In hac habitasse platea dictumst.  In ac tempor quam. Vestibulum eleifend vehicula ligula, et cursus nisl gravida sit
      amet. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.</p>
  </div>
</div>


<script>
  function growDiv() {
    var growDiv = document.getElementById('grow');
    if (growDiv.clientHeight) {
      growDiv.style.height = 0;
    } else {
      var wrapper = document.querySelector('.measuringWrapper');
      growDiv.style.height = wrapper.clientHeight + "px";
    }
    /*document.getElementById("more-button").value = document.getElementById("more-button").value == 'Read more' ? 'Read less' : 'Read more';*/
  }
</script>