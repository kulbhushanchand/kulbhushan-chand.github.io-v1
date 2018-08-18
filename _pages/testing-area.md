---
layout: page
title: Testing area
subtitle: Nothing meaningful here
bigimg: null
tags:
  - testing
published: true
ext-lib:
  - academicon
  - animate
  - wow
  - aos
  - mathjax
  - mermaid
  - chartjs
  - baffle
  - typed
---


<div class="mobile-js-hide">
  <div class="row">
    <div class="col-sm-12">
      <div style="color:#890000">
        <h2> <span class="typedLine1" style="color:#32662a" ></span></h2> 
      </div>
    </div>
  </div>
 </div>    


# First post t26

this is the mermaid diagram -

## First post

this is the mermaid diagram -

### First post

this is the mermaid diagram -

#### First post

this is the mermaid diagram -



<div class="mermaid">
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
</div>




- [x] a task list item
- [ ] list syntax required
- [ ] normal **formatting**, @mentions, #1234 refs
- [ ] incomplete
- [x] completed







<i class="ai ai-coursera ai-5x"></i>


<i style="color: Tomato;" class="fas fa-stroopwafel fa-3x"></i>

<div class="item" data-aos="fade-up"> kulbhushan AOS animation </div>



<div class="wow zoomIn" data-wow-duration="0.5s">
 kulbhushan WOW animation
</div>


<canvas id="bar-chart-horizontal" width="800" height="450"></canvas>
<script>
new Chart(document.getElementById("bar-chart-horizontal"), {
    type: 'horizontalBar',
    data: {
      labels: ["Africa", "Asia", "Europe", "Latin America", "North America"],
      datasets: [
        {
          label: "Population (millions)",
          backgroundColor: ["#3e95cd", "#8e5ea2","#3cba9f","#e8c3b9","#c45850"],
          data: [2478,5267,734,784,433]
        }
      ]
    },
    options: {
      legend: { display: false },
      title: {
        display: true,
        text: 'Predicted world population (millions) in 2050'
      }
     
    }
});
 
</script>


<script>
    var b = window.baffle('h4', 
     { characters: 'b6c7807bb10b5d867000',// ▓░█ ▒░▒▓░ ▒░░▓> ▒█▓ █░><▒ █▒█▓ ▓░/ ▓▓/█ █▓▒', 
      speed: 50 });
  b.start().once().reveal(500, 500);
</script>



<script>
var typed = new Typed( '.typedLine1', {
  strings: [" Nothing meaningful ^500 <span style='color:#890000; font-weight:bold;'>here</span>" ,
            " Nothing meaningful ^500 <span style='color:#890000; font-weight:bold;'>there</span>", 
            " Nothing meaningful ^500 <span style='color:#890000; font-weight:bold;'>anywhere</span>", 
            " It's a silly ^1000 <span style='color:#890000; font-weight:bold;'>World !!!</span>"],
  startDelay: 1000,
  typeSpeed: 65,
  backSpeed: 60,
  backDelay: 500,
  showCursor: true,
  smartBackspace: true, // this is a default
  loop: false,
  fadeOut: false,
  shuffle: false
});
</script>


<script>
var typed = new Typed( '', {
  strings: ["Technology.","Open Source.","Science."],
  startDelay: 1000,
  typeSpeed: 100,
  backSpeed: 0,
  backDelay: 1000,
  showCursor: true,
  smartBackspace: true, // this is a default
  loop: true,
  fadeOut: false,
  shuffle: false
});
</script>

