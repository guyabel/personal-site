---
# An instance of the Blank widget.
# Documentation: https://wowchemy.com/docs/getting-started/page-builder/
widget: blank

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 35

title: R Packages
subtitle: Click on the hex sticker to visit pkgdown sites.

design:
  columns: "2"
  spacing:
    padding: ["50px", "50px", "50px", "50px"]
---

<!-- 
1. Place hex sticker image in the /static/media folder
2. Fill in the list item template below for each hex sticker and insert within hexGrid list below 
<li class="hex">
  <div class="hexIn">
    <a class="hexLink" href=" ***insert link to package*** ">
      <img src=" *** insert link to hex sticker *** " alt="" />
      <h1> *** insert package name *** </h1>
      <p> *** insert short package description *** </p>
    </a>
  </div>
</li>
3. Place hexagons.css into /static/css folder and customize
4. Add package to config/_default/menus.yaml
-->


<link rel="stylesheet" type="text/css" href="/css/hexagons.css">

<ul id="hexGrid">
  <li class="hex">
    <div class="hexIn">
      <a class="hexLink" href="https://guyabel.github.io/wcde/">
        <img src="/media/hex_wcde.png" alt="" />
        <h1>wcde</h1>
        <p>Download data from the Wittgenstein Centre Human Capital Data Explorer</p>
      </a>
    </div>
  </li>
  <li class="hex">
    <div class="hexIn">
      <a class="hexLink" href="https://guyabel.github.io/migest/">
        <img src="/media/hex_migest.png" alt="" />
        <h1>migest</h1>
        <p>Tools for estimating, measuring and working with migration data.</p>
      </a>
    </div>
  </li>
  <li class="hex">
    <div class="hexIn">
      <a class="hexLink" href="https://guyabel.github.io/fanplot/">
        <img src="/media/hex_fanplot.png" alt="" />
        <h1>fanplot</h1>
        <p>Visualising sequential probability distributions using fan charts</p>
      </a>
    </div>
  </li>
  <li class="hex">
    <div class="hexIn">
      <a class="hexLink" href="https://guyabel.github.io/tidycat/">
        <img src="/media/hex_tidycat.png" alt="" />
        <h1>tidycat</h1>
        <p>Create additional rows and columns on broom::tidy() output. </p>
      </a>
    </div>
  </li>
</ul>