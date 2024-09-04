---
title: Conjugate Heat Transfer of a Compressible Fluid
description:
layout: default
---

<div style="text-align: justify;">    
    In this project, we analyze a compressible airflow involving Conjugate Heat Transfer (CHT) using CFX. The study focuses on a laminar internal flow of air drawn from a cloud chamber (AIDAd) to an aerosol spectrometer (Welas), where it undergoes heating during circulation. This heating can be detrimental to water and ice particles, making it crucial to investigate. The project examines the use of thermal insulation to mitigate this effect. Heat exchange with the external air is modeled using correlations to calculate the Nusselt number, which is then employed to determine the heat transfer coefficient (h).
    
</div>

<div class="figure-container">
    <figure>
        <img src="assets/photo-1.jpg" alt="System Setup Photo" style="width:100%;"/>
         <figcaption>Figure 1: System Setup.</figcaption>
    </figure>
</div>  
    
<h1>Introduction</h1>

<div style="text-align: justify;">
    A technical drawing is shown in Figure 1. The air flows downwards, crossing three different regions: the first, characterized by being the pipe inside an inner chamber with a temperature of -20°C and a length of 250 mm; the second, with a length of 570 mm and located in the gap between the inner and outer vessels; and the third, where the pipe extends from the external vessel to the aerosol spectrometer.
</div>    

<div class="figure-container">
    <figure>
        <img src="assets/real-geometry-1.png" alt="System Setup Diagram" style="width:60%;"/>
         <figcaption>Figure 2: Schematic section of connection system: components and dimensions.</figcaption>
    </figure>
</div>  

<div style="text-align: justify;">
    On one hand, the PTFE seal component prevents cold air from escaping the inner chamber. On the other hand, the flange component, in contact with the external vessel, ensures that the air in the gap remains contained.

    In the following section, and based on the foregoing description, the CFD model will be presented. The CFD domain, along with the boundary conditions, the mesh, and the most relevant features, will be described.
</div> 

<h1>CFD Model</h1>
<h2>Code, Domain and Physical Porperties.</h2>

<div class="figure-container">
    <figure>
        <img src="assets/geometries-1.png" alt="CFD Domain Diagrams" style="width:60%;"/>
         <figcaption>Figure 2: Section of the geometry considered in the simulations with (right) and without (left) thermal insulator. Dimensions and boundary conditions are depicted.</figcaption>
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





