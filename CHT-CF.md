---
title: Conjugate Heat Transfer of a Compressible Fluid
description:
layout: default
---

<div style="text-align: justify;">    
    In this project, we analyze a compressible airflow involving Conjugate Heat Transfer (CHT) using CFX. The study focuses on a laminar internal flow of air drawn from a cloud chamber (AIDAd) to an aerosol spectrometer (Welas), where it undergoes heating during circulation. This heating can be detrimental to water and ice particles, making it crucial to investigate. The project examines the use of thermal insulation to mitigate this effect. Heat exchange with the external air is modeled using correlations to calculate the Nusselt number, which is then employed to determine the heat transfer coefficient (h).


    <div class="figure-container">
        <figure>
            <img src="assets/photo-1.jpg" alt="System Setup Photo" style="width:100%;"/>
             <figcaption>Figure 1: System Setup.</figcaption>
        </figure>
    </div>  
</div>

<h1>Introduction</h1>

<div style="text-align: justify;">
    A technical drawing is shown in Figure 1. The air flows downwards, crossing three different regions: the first, characterized by being the pipe inside an inner chamber with a temperature of -20°C and a length of 250 mm; the second, with a length of 570 mm and located in the gap between the inner and outer vessels; and the third, where the pipe extends from the external vessel to the aerosol spectrometer.
</div>    

<div class="figure-container">
    <figure>
        <img src="assets/real-geometry-1.png" alt="System Setup Diagram" style="width:50%;"/>
         <figcaption>Figure 2: Schematic section of connection system: components and dimensions.</figcaption>
    </figure>
</div>    

<div class="table-container">
    <table>
        <tablecaption>Table 1: Components and Materials List</tablecaption>
        <thead>
            <tr>
                <th>Component</th>
                <th>Material</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Tube, Collar and Flange</td>
                <td>SS 304L</td>
            </tr>
            <tr>
                <td>PTFE Seal</td>
                <td>PTFE</td>
            </tr>
            <tr>
                <td>Spring</td>
                <td>---</td>
            </tr>
        </tbody>
    </table>
</div>





