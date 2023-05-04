---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

<style>
h4 {
  text-align:center;
}
div {
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
  display: table;
}
img {
  display:table-cell;
  text-align:center;
  vertical-align:middle;
  border-radius:10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display:table-cell;
  background:white;
  border-radius:20px;
  height:auto;
}
iframe {
  margin:0;
  padding:0;
  width:175px;
  display:inline;
  vertical-align:middle;
}
</style>

## Research

<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>Design of Flexures based on Compliant Building Elements (CBE)</h4>

<p style="text-align: justify;">Compliant Building Elements (CBE) is a novel and systematic method for generating practicable flexure designs. The CBE is unique in that it encodes a compliant system’s quantitative information, including elasticity, geometry, location, and orientation, in a parametric matrix. In CBE, a compliant system consists of three types of compliant elements, i.e., compliant elements formed by serial or parallel connections and basic compliant elements. The synthesis procedure is a top-down and iterative process, starting from laying out the stage topology to finally optimizing the compliant connection elements and types. The matrix-based synthesis for compliant mechanisms is analogous to the screw-based type synthesis for rigid parallel mechanisms, and enables early-stage flexure system design via building compliant blocks just like building LEGO<sup>®</sup> bricks.</p>

</div>
<div class="row justify-content-center">
<div class="col-md-8 col-sm-12" style="background-color:white;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/CBE.png" width="100%"/>
</div>
</div>
</div>

<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>Deep Learning-based Precision Control for Nanopositioner</h4>

<p style="text-align: justify;">We present a new control method for compliant mechanisms based on deep learning models that achieve 100 nm precision in multiple axes with low-lost strain sensor arrays. In our setup, the strain sensor arrays are applied to the flexing components on a custom-designed six-axis compliant nanopositioner such that it measures the mechanical strain for real-time control. We demonstrate that the deep model developed based on the deep reinforcement learning method can fully replace the classical proportional–integral–derivative (PID) controller, realizing 100 nm precision without tuning any control parameters. This implementation and control method can be utilized for all kinds of flexural systems and enable low-cost and user-friendly precision platforms without compromising performance.</p>

</div>
<div class="row justify-content-center">
<div class="col-md-8 col-sm-12 " style="background-color:white;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/DLPC.png" width="100%"/>
</div>
</div>
</div>

<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>Precision Multi-layer Roll-to-roll Printing System</h4>

<p style="text-align: justify;">We have developed a multi-layer roll-to-roll (R2R) system with multiple-input multiple-output (MIMO) closed-loop control that achieves submicron-level alignment precision for large-scale continuous printing processes. The enabling elements in the multi-layer R2R system include (1) a new vision-based alignment algorithm/method, which provides 100s nm position detection capability based on low-cost cameras; and (2) a custom-built five-axis compliant roller positioner, which has a ±1 mm range with 100s nm precision in <i>X</i>, <i>Y</i>, and <i>Z</i> axes respectively. Based on the new methods, a gate/source-drain multi-layer electrode structure for field-effect transistors (FETs) has been designed and fabricated on a 4-inch PET web, demonstrating better than 1 μm overlay precision in fabricating flexible electronics on a R2R platform for the first time.</p>

</div>
<div class="row justify-content-center">
<div class="col-md-8 col-sm-12" style="background-color:white;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/R2R.png" width="100%"/>
</div>
</div>
</div>

<div class="jumbotron">
<h4>Dynamic-tunable Nanopositioner for Parallel Nanomanufacturing</h4>
<div class="row align-items-center">
<div class="col-md-8 col-sm-12">

<p style="text-align: justify;">We present the design and control of a flexure-based five-axis nanopositioner with dynamic-tuning capability for parallel nanomanufacturing applications. The dynamic-tuning method enables trade-offs between the range and speed of the nanopositioner so as to increase the throughput of the nanomanufacturing system. The nanopositioner conforms with the in-plane range and resolution requirements, i.e., ±5 mm/100 nm in the <i>X</i>/<i>Y</i> axis, while its natural frequencies in the <i>X</i>/<i>Y</i> axis can be increased by two to three times at the expense of decreased stroke. Nano-scratching experiments were performed using an 18-tip AFM (atomic force microscopy) array to fabricate optical grating patterns on gold-coated silicon substrates of 5×1 mm<sup>2</sup> to demonstrate the practicality of the new method.</p>

</div>
<div class="col-md-4 col-sm-12" style="background-color:white;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/Dyn.png" style="width: 100%;"/>
</div>
</div>
</div>

<div class="jumbotron">
<h4>High-speed Oscillating Blade Microtome</h4>
<div class="row align-items-center">
<div class="col-md-9 col-sm-12">

<p style="text-align: justify;">We theoretically and experimentally study the cutting mechanism of soft materials using a custom-built oscillating blade microtome. Analytical models are derived to deterministically link the sectioning quality to the cutting parameters, including blade oscillation frequency, amplitude, and sample feed rate. Importantly, for the first time, the study reveals that the sectioning results given by microtomes can be greatly enhanced when the cutting frequency is above 150 Hz due to the material stiffening effect—a unique trait of viscoelastic materials. The model may be used to predict the optimal cutting parameters for various tissues. As most state-of-the-art microtomes operate below 100 Hz, the results also set new requirements for next-generation tissue sectioning and surgical instruments.</p>

</div>
<div class="col-md-3 col-sm-12" style="background-color:white;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/Vib.jpg" width="100%"/>
</div>
</div>
</div>
