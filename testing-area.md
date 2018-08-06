---
layout: page
title: Testing area
subtitle: Nothing meaningful here
bigimg: null
tags:
  - testing
published: true
---


# First post

this is the mermaid diagram -


<div class="mermaid">

graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;

</div>



- [ ] a task list item
- [ ] list syntax required
- [ ] normal **formatting**, @mentions, #1234 refs
- [ ] incomplete
- [x] completed




<i class="ai ai-coursera ai-5x"></i>


<i style="color: Tomato;" class="fas fa-stroopwafel fa-3x"></i>

<div class="item" data-aos="fade-up"> <h1> kulbhushan AOS animation</h1> </div>



<div class="wow zoomIn" data-wow-duration="0.5s">
<h2> kulbhushan WOW animation</h2>
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

 