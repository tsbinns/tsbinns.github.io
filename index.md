<!-- Alert bar: "Use Chrome!" -->
<div id="hellobar-bar" class="regular closable">
    <div class="hb-content-wrapper">
        <div class="hb-text-wrapper">
            <div class="hb-headline-text">
                <p><span>For the intended website experience, please use Google Chrome.</span></p>
            </div>
        </div>
    </div>
    <div class="hb-close-wrapper">
        <a href="javascript:void(0);" class="icon-close">&#10006;</a>
    </div>
</div>
body{
    margin: 0;
    padding: 0;
    width: 100%;
}
#hellobar-bar {
    font-family: "Open Sans", sans-serif;
    width: 100%;
    margin: 0;
    height: 30px;
    display: table;
    font-size: 17px;
    font-weight: 400;
    padding: .33em .5em;
    -webkit-font-smoothing: antialiased;
    color: #5c5e60;
    position: fixed;
    background-color: white;
    box-shadow: 0 1px 3px 2px rgba(0,0,0,0.15);
}
#hellobar-bar.regular {
    height: 30px;
    font-size: 14px;
    padding: .2em .5em;
}
.hb-content-wrapper {
    text-align: center;
    text-align: center;
    position: relative;
    display: table-cell;
    vertical-align: middle;
}
.hb-content-wrapper p {
    margin-top: 0;
    margin-bottom: 0;
}
.hb-text-wrapper {
    margin-right: .67em;
    display: inline-block;
    line-height: 1.3;
}
.hb-text-wrapper .hb-headline-text {
    font-size: 1em;
    display: inline-block;
    vertical-align: middle;
}
#hellobar-bar .hb-cta {
    display: inline-block;
    vertical-align: middle;
    margin: 5px 0;
    color: #ffffff;
    background-color: #22af73;
    border-color: #22af73
}
.hb-cta-button {
    opacity: 1;
    color: #fff;
    display: block;
    cursor: pointer;
    line-height: 1.5;
    max-width: 22.5em;
    text-align: center;
    position: relative;
    border-radius: 3px;
    white-space: nowrap;
    margin: 1.75em auto 0;
    text-decoration: none;
    padding: 0;
    overflow: hidden;
}
.hb-cta-button .hb-text-holder {
    border-radius: inherit;
    padding: 5px 15px;
}
.hb-close-wrapper {
    display: table-cell;
    width: 1.6em;
}
.hb-close-wrapper .icon-close {
    font-size: 14px;
    top: 15px;
    right: 25px;
    width: 15px;
    height: 15px;
    opacity: .3;
    color: #000;
    cursor: pointer;
    position: absolute;
    text-align: center;
    line-height: 15px;
    z-index: 1000;
    text-decoration: none;
}
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<a href="javascript:void(0);" class="icon-close" onclick="$('#use_chrome-bar').fadeOut()">&#10006;</a>

---
title: "About Me - Thomas Samuel Binns"
layout: page
---


<!-- Profile picture -->
<img width="25%" height="auto" style="float: left; margin-right: 20px;" src="/assets/images/ProfilePic.png">


<!-- Main website description/introduction -->
I am a neuroscientist from the UK interested in computational, cognitive, and translational neuroscience, with a particular interest in neuromodulation and brain-computer interfaces.

I have recently graduated with First-Class Honours in an M.Sci. Neuroscience with Psychology degree at the University of Aberdeen, UK. This included 12 months spent on placement at the Bernstein Center for Computational Neuroscience, Germany, investigating volition and decision-making using brain-computer interfaces in the lab of Prof. John-Dylan Haynes.

I am scheduled to begin my Ph.D. at the Einstein Center for Neurosciences Berlin, Germany, in October 2021.

Feel free to check out my [CV](/CV.html) and [publications](/publications.html), or contact me [here](/contact-links.html).
