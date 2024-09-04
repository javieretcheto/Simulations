---
title: Conjugate Heat Transfer of a Compressible Fluid
---

<div style="text-align: justify;">    
    In this project, we analyze a compressible airflow involving Conjugate Heat Transfer (CHT) using CFX. The study focuses on a laminar internal flow of air drawn from a cloud chamber (AIDAd) to an aerosol spectrometer (Welas), where it undergoes heating during circulation. This heating can be detrimental to water and ice particles, making it crucial to investigate. The project examines the use of thermal insulation to mitigate this effect. Heat exchange with the external air is modeled using correlations to calculate the Nusselt number, which is then employed to determine the heat transfer coefficient (h).


    <div style="text-align: center;">
        <img src="assets/photo-1.jpg" alt="CFD Project" style="width:100%;"/>
    </div>
    
</div>

<div style="text-align: justify;">
    <h1>Introduction</h1>

    A technical drawing is shown in Figure 1. The air flows downwards, crossing three different regions: the first, characterized by being the pipe inside an inner chamber with a temperature of -20°C and a length of 250 mm; the second, with a length of 570 mm and located in the gap between the inner and outer vessels; and the third, where the pipe extends from the external vessel to the aerosol spectrometer.
    
    <div style="text-align: center;">
        <img src="assets/real-geometry-1.jpg" alt="CFD Project" style="width:100%;"/>
    </div>



</div>

| Component              |    Material   |
|------------------------|---------------|
| Tube, Collar and Flange|    SS 304L    |
| PTFE Seal              |     PTFE      |
| Spring                 |     ----      |
