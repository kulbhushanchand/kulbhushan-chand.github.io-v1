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
---

<div> kbc </div>

<script>
        /* set up XMLHttpRequest */
        var url = "Kulbhushan-Chand.github.io/img/Test.xlsx";
        var oReq = new XMLHttpRequest();
        oReq.open("GET", url, true);
        oReq.responseType = "arraybuffer";
 
        oReq.onload = function(e) {
            var arraybuffer = oReq.response;
 
            /* convert data to binary string */
            var data = new Uint8Array(arraybuffer);
            var arr = new Array();
            for (var i = 0; i != data.length; ++i) arr[i] = String.fromCharCode(data[i]);
            var bstr = arr.join("");
 
            /* Call XLSX */
            var workbook = XLSX.read(bstr, {
                type: "binary"
            });
 
            /* DO SOMETHING WITH workbook HERE */
            var first_sheet_name = workbook.SheetNames[0];
            /* Get worksheet */
            var worksheet = workbook.Sheets[first_sheet_name];
            console.log(XLSX.utils.sheet_to_json(worksheet, {raw: true}));
        }
 
        oReq.send();
 </script>


# First post

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



- [ ] a task list item
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

