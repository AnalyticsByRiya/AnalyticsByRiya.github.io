---
layout: default 
title: Riya Biju Ollukaran - Spatial Data Science Portfolio
---

<!-- Core Portfolio Styling -->
<style>
  :root {
    --primary-blue: #0284c7;
    --primary-green: #059669;
    --dark-slate: #0f172a;
    --body-gray: #334155;
    --light-bg: #f8fafc;
    --border-gray: #e2e8f0;
  }
  
  .portfolio-container {
    max-width: 1140px;
    margin: 0 auto;
    padding: 20px;
    font-family: 'Inter', -apple-system, sans-serif;
    color: var(--dark-slate);
    line-height: 1.6;
  }

  .section-title {
    font-size: 1.75rem;
    font-weight: 800;
    text-transform: uppercase;
    letter-spacing: 0.05em;
    margin-top: 50px;
    margin-bottom: 25px;
    padding-bottom: 10px;
    border-bottom: 2px solid var(--border-gray);
  }

  .grid-card {
    display: grid;
    grid-template-columns: 1.2fr 0.8fr;
    gap: 40px;
    background: #ffffff;
    border: 1px solid var(--border-gray);
    border-radius: 16px;
    padding: 35px;
    margin-bottom: 35px;
    box-shadow: 0 4px 6px -1px rgba(0,0,0,0.02), 0 10px 15px -3px rgba(0,0,0,0.03);
    align-items: start;
  }

  .grid-card.reverse {
    grid-template-columns: 0.8fr 1.2fr;
  }

  .pipeline-box {
    background: var(--light-bg);
    border: 1px dashed #cbd5e0;
    padding: 15px;
    border-radius: 8px;
    margin: 18px 0;
  }

  .tech-badge {
    display: inline-block;
    padding: 4px 10px;
    border-radius: 6px;
    font-size: 0.8rem;
    font-weight: 600;
    margin-right: 6px;
    margin-bottom: 6px;
  }

  .badge-gis { background: #e0f2fe; color: #0366d6; }
  .badge-3d { background: #ffedd5; color: #ea580c; }
  .badge-ds { background: #ecfdf5; color: #059669; }
  .badge-meta { background: #f1f5f9; color: #475569; }

  @media (max-width: 768px) {
    .grid-card, .grid-card.reverse {
      grid-template-columns: 1fr;
      padding: 20px;
    }
    .grid-card .visual-pane {
      order: -1;
    }
  }
</style>

<div class="portfolio-container">

  <!-- HERO HEADER SECTION -->
  <header style="text-align: center; padding: 40px 0 20px 0; margin-bottom: 40px;">
    <h1 style="font-size: 3rem; font-weight: 800; color: var(--dark-slate); margin-bottom: 5px; letter-spacing: -0.03em;">Riya Biju Ollukaran</h1>
    <p style="font-size: 1.3rem; color: var(--primary-blue); margin-top: 0; font-weight: 500;">Spatial Data Scientist & 3D Environment Specialist</p>
    
    <p style="max-width: 750px; margin: 20px auto; color: var(--body-gray); font-size: 1.1rem;">
      Final-Year Master of Data Science student at Monash University. Fusing Data Science with geospatial mechanics (ArcGIS, QGIS, Blender) to translate spatial telemetry into high-fidelity environments.
    </p>

    <div style="margin-top: 15px; font-size: 0.95rem; color: #64748b;">
      📍 Melbourne, Australia | ✉️ riyabijuollukaran@gmail.com | 🔗 <a href="https://www.linkedin.com/in/riya-biju-ollukaran/" target="_blank" style="color: var(--primary-blue); text-decoration: none; font-weight: 600;">LinkedIn</a>
    </div>
  </header>

  <!-- BANNER MEDIA CONTAINER -->
  <div style="width: 100%; border-radius: 16px; overflow: hidden; margin-bottom: 5px; box-shadow: 0 10px 25px -5px rgba(0,0,0,0.05);">
    <video width="100%" autoplay loop muted playsinline style="display: block;">
      <source src="assets/video/GIS Personal LinkedIn Banner.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>

  <!-- SECTION I: GEOSPATIAL & 3D TOPOGRAPHIC MODELING -->
  <h2 class="section-title" style="color: var(--primary-blue); border-color: var(--primary-blue);">I. Geospatial Analysis & 3D Topographic Modeling</h2>

  <!-- PROJECT 1: Galapagos 3D Modeling (Digital Twin Frame) -->
  <article class="grid-card">
    <div>
      <span style="font-size: 0.8rem; font-weight: 700; color: #b45309; letter-spacing: 0.05em; text-transform: uppercase;">[High Complexity] Digital Twin Prototype</span>
      <h3 style="font-size: 1.8rem; margin: 5px 0 10px 0; color: var(--dark-slate);">3D Geospatial Visualization: Galapagos Archipelago Case Study</h3>
      <p style="margin: 0; font-size: 0.9rem; color: #64748b; font-style: italic;">The School of Information Design | Under Instruction of Elizabeth Rosenbloom</p>
      
      <div class="pipeline-box">
        <strong style="display: block; font-size: 0.75rem; color: #64748b; margin-bottom: 5px; text-transform: uppercase;">Data Pipeline Architecture:</strong>
        <div style="font-family: monospace; font-size: 0.85rem; color: #0f172a;">
          Raw Raster DEM ➔ Coordinate Alignment (WGS 84 / EPSG:4326) ➔ Mesh Extrusion (Blender Modifiers) ➔ Procedural Node Displacement Shading
        </div>
      </div>

      <ul style="padding-left: 20px; color: var(--body-gray);">
        <li style="margin-bottom: 8px;"><strong>Pipeline Engineering:</strong> Built an uncompressed, non-destructive spatial asset extraction process to translate raw GIS elevation models directly into structural render meshes.</li>
        <li style="margin-bottom: 8px;"><strong>Topographical Alignment:</strong> Resolved systemic software unit-mismatches by re-projecting base source layers to ensure geographic coordinate accuracy.</li>
        <li style="margin-bottom: 8px;"><strong>Procedural Node Development:</strong> Engineered complex, object-space procedural shader nodes within Blender to accurately model micro-wave pattern distributions across deep water interfaces.</li>
      </ul>

      <div style="margin-top: 15px;">
        <span class="tech-badge badge-gis">QGIS</span>
        <span class="tech-badge badge-3d">Blender 3D</span>
        <span class="tech-badge badge-gis">DEM Modeling</span>
        <span class="tech-badge badge-meta">WGS 84</span>
      </div>
    </div>
    
    <div class="visual-pane" style="display: flex; flex-direction: column; gap: 10px;">
      <img src="assets/img/GalapagosRendered.png" alt="Galapagos 3D Render View" style="width: 100%; height: 160px; object-fit: cover; border-radius: 8px; border: 1px solid var(--border-gray);">
      <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 10px;">
        <img src="assets/img/v2_Galapagos_DEM.png" alt="Galapagos DEM Spatial File" style="width: 100%; height: 100px; object-fit: cover; border-radius: 8px; border: 1px solid var(--border-gray);">
        <img src="assets/img/BlenderScreenSS.png" alt="Blender Mapping Interface" style="width: 100%; height: 100px; object-fit: cover; border-radius: 8px; border: 1px solid var(--border-gray);">
      </div>
    </div>
  </article>

  <!-- PROJECT 2: South Africa Bush Lodges MCE -->
  <article class="grid-card reverse">
    <div class="visual-pane">
      <img src="assets/img/Kruger_Lodge_Suitability_Map.jpg" alt="South Africa Bush Lodge Suitability Analysis Output Map" style="width: 100%; border-radius: 12px; border: 1px solid var(--border-gray); box-shadow: 0 4px 12px rgba(0,0,0,0.05);">
    </div>
    
    <div>
      <span style="font-size: 0.8rem; font-weight: 700; color: var(--primary-blue); letter-spacing: 0.05em; text-transform: uppercase;">[Medium Complexity] Land Suitability Analysis</span>
      <h3 style="font-size: 1.8rem; margin: 5px 0 10px 0; color: var(--dark-slate);">Suitable Sites for Remote Bush Lodges in Northeastern South Africa</h3>
      <p style="margin: 0; font-size: 0.9rem; color: #64748b; font-style: italic;">Monash University | EAE5258 – GIS for Environmental Sciences</p>
      
      <div class="pipeline-box">
        <strong style="display: block; font-size: 0.75rem; color: #64748b; margin-bottom: 5px; text-transform: uppercase;">Data Pipeline Architecture:</strong>
        <div style="font-family: monospace; font-size: 0.85rem; color: #0f172a;">
          7 Vector/Raster Inputs ➔ Africa Albers Equal Area Projection ➔ Topo to Raster DEM Integration ➔ Multi-Criteria Reclassification ➔ Boolean Overlay
        </div>
      </div>

      <ul style="padding-left: 20px; color: var(--body-gray);">
        <li style="margin-bottom: 8px;"><strong>Multi-Criteria Evaluation (MCE):</strong> Standardized 7 separate datasets by resolving structural vector defects and coordinate shifts across administrative maps.</li>
        <li style="margin-bottom: 8px;"><strong>Terrain Derivation:</strong> Extracted continuous slope gradients and directional aspect configurations using spatial mathematical matrices from contours.</li>
        <li style="margin-bottom: 8px;"><strong>Environmental Filtering:</strong> Executed raster calculator logic loops and mathematical constraints, identifying 263 low-impact environmental candidate locations across the Kruger National Park layout.</li>
      </ul>

      <div style="margin-top: 15px;">
        <span class="tech-badge badge-gis">ArcGIS Pro</span>
        <span class="tech-badge badge-gis">Spatial Analyst</span>
        <span class="tech-badge badge-meta">MCE Matrix</span>
      </div>
    </div>
  </article>

  <!-- PROJECT 3: San Francisco Greenspace Analysis -->
  <article class="grid-card">
    <div>
      <span style="font-size: 0.8rem; font-weight: 700; color: #7c3aed; letter-spacing: 0.05em; text-transform: uppercase;">[Low/Med Complexity] Urban Analytics Matrix</span>
      <h3 style="font-size: 1.8rem; margin: 5px 0 10px 0; color: var(--dark-slate);">San Francisco Mapping: Urban Green Spaces Project Evaluation</h3>
      <p style="margin: 0; font-size: 0.9rem; color: #64748b; font-style: italic;">Independent Geospatial Certification Focus</p>
      
      <p style="color: var(--body-gray); margin-top: 15px;">
        An urban assessment model checking local public park accessibility thresholds and density distribution spreads across metropolitan San Francisco boundaries. Evaluated infrastructural park access by matching regional civic vectors against community boundaries.
      </p>

      <ul style="padding-left: 20px; color: var(--body-gray);">
        <li style="margin-bottom: 8px;">Analyzed neighborhood location access variances by configuring demographic distribution buffers against spatial polygon layouts.</li>
        <li style="margin-bottom: 8px;">Generated spatial scores shown explicitly inside the formal map artifact titled <strong>SF Parks Evaluation.jpg</strong>.</li>
      </ul>

      <div style="margin-top: 25px;">
        <span class="tech-badge badge-gis">ArcGIS</span>
        <span class="tech-badge badge-meta">Urban Networks</span>
        <a href="https://coursera.org/share/444f44ed46f7be52f5736cf9c1595938" target="_blank" style="margin-left: 10px; font-size: 0.85rem; color: var(--primary-blue); font-weight: 700; text-decoration: none;">Verify Credential ↗</a>
      </div>
    </div>
    
    <div class="visual-pane">
      <img src="assets/img/SF Parks Evaluation.jpg" alt="SF Parks Evaluation.jpg Asset Map Page" style="width: 100%; border-radius: 12px; border: 1px solid var(--border-gray); box-shadow: 0 4px 12px rgba(0,0,0,0.05);">
    </div>
  </article>


  <!-- SECTION II: DATA SCIENCE FRAMEWORKS & SPATIOTEMPORAL DASHBOARDS -->
  <h2 class="section-title" style="color: var(--primary-green); border-color: var(--primary-green);">II. Data Science & Narrative Dashboards</h2>

  <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(480px, 1fr)); gap: 30px; margin-bottom: 5px;">
    
    <!-- PROJECT 4: AI Outbreak Spotting (Data Science Module) -->
    <article style="background: #ffffff; border: 1px solid var(--border-gray); border-radius: 16px; padding: 30px; box-shadow: 0 4px 6px -1px rgba(0,0,0,0.02); display: flex; flex-direction: column; justify-content: space-between;">
      <div>
        <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 10px;">
          <h3 style="margin: 0; font-size: 1.4rem; color: var(--dark-slate);">AI-Powered Pandemic Early Detection System</h3>
          <span style="color: #64748b; font-size: 0.85rem; font-weight: 600;">Monash University</span>
        </div>
        <p style="color: var(--body-gray); font-size: 0.95rem; line-height: 1.6;">
          Engineered an analytics architecture model utilizing multi-stream inputs (wastewater, mobility logs, historical patterns) to pinpoint initial public health anomalies. 
        </p>
        <ul style="padding-left: 20px; font-size: 0.9rem; color: var(--body-gray);">
          <li style="margin-bottom: 6px;">Evaluated deep historical CDC FluView tracking layers using R frameworks (`dplyr`, `ggplot2`).</li>
          <li style="margin-bottom: 6px;">Achieved an ~80% analytical sensitivity metric across early anomaly signal variations, earning academic Distinction.</li>
        </ul>
      </div>
      
      <div style="margin-top: 20px; padding-top: 15px; border-top: 1px solid var(--border-gray);">
        <span class="tech-badge badge-ds">R Core</span>
        <span class="tech-badge badge-ds">Time-Series</span>
        <span class="tech-badge badge-meta">Predictive Modeling</span>
      </div>
    </article>

    <!-- PROJECT 5: Arctic Circle Change (Spatiotemporal Track) -->
    <article style="background: var(--dark-slate); color: #ffffff; border-radius: 16px; padding: 30px; display: flex; flex-direction: column; justify-content: space-between; border-top: 4px solid var(--primary-green);">
      <div>
        <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 10px;">
          <h3 style="margin: 0; font-size: 1.4rem; color: #ffffff;">Arctic Circle Environmental Change Visualizer</h3>
          <span style="background: #b91c1c; color: white; padding: 2px 8px; border-radius: 4px; font-size: 0.75rem; font-weight: 700; letter-spacing: 0.05em;">ONGOING DEVELOPER PIPELINE</span>
        </div>
        <p style="color: #94a3b8; font-size: 0.95rem; font-weight: 500;">Monash University | FIT5147 – Data Visualization Focus</p>
        
        <p style="color: #cbd5e1; font-size: 0.95rem; line-height: 1.6; margin-top: 15px;">
          Designing an interactive narrative visualization application engine to explore the overlapping environmental impacts of systemic polar shifts.
        </p>
        <ul style="padding-left: 20px; font-size: 0.9rem; color: #cbd5e1;">
          <li style="margin-bottom: 6px;">Consolidating long-term spatio-temporal logs tracking sea ice anomalies (1978–2026) alongside satellite GPS coordinates.</li>
          <li style="margin-bottom: 6px;">Integrating synchronized dashboards deploying active Leaflet mapping frameworks to capture how resource tracking overlaps commercial shipping channels.</li>
        </ul>
      </div>

      <div style="margin-top: 20px; padding-top: 15px; border-top: 1px solid #334155;">
        <span class="tech-badge" style="background: #1e293b; color: #34d399; border: 1px solid #334155;">R Shiny</span>
        <span class="tech-badge" style="background: #1e293b; color: #38bdf8; border: 1px solid #334155;">Leaflet Spatial</span>
        <span class="tech-badge" style="background: #1e293b; color: #a78bfa; border: 1px solid #334155;">Spatiotemporal Modeling</span>
      </div>
    </article>

  </div>


  <!-- RESTRUCTURED CORE METADATA SECTIONS -->
  <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 30px; margin-top: 5px;">
    
    <!-- SKILLS MATRIX -->
    <section style="background: #ffffff; border: 1px solid var(--border-gray); padding: 25px; border-radius: 12px;">
      <h4 style="margin-top: 0; color: var(--dark-slate); font-size: 1.2rem; border-left: 4px solid var(--primary-blue); padding-left: 10px;">Technical Stack Matrix</h4>
      <ul style="padding-left: 20px; color: var(--body-gray); font-size: 0.95rem;">
        <li style="margin-bottom: 6px;"><strong>Spatial & Analytics:</strong> ArcGIS, ArcGIS Pro, QGIS, Blender 3D (Cycles Engine), Spatial Analyst toolkit frameworks</li>
        <li style="margin-bottom: 6px;"><strong>Data Ecosystems:</strong> Python (Pandas, Scikit-Learn), R (Dplyr, Ggplot2), Oracle SQL Developer Database structures</li>
        <li style="margin-bottom: 6px;"><strong>Operational Tools:</strong> Version Control (GitLab, Git pipeline structures), Jira Management, Excel</li>
      </ul>
    </section>

    <!-- EDUCATION & CERTIFICATIONS -->
    <section style="background: #ffffff; border: 1px solid var(--border-gray); padding: 25px; border-radius: 12px;">
      <h4 style="margin-top: 0; color: var(--dark-slate); font-size: 1.2rem; border-left: 4px solid var(--primary-green); padding-left: 10px;">Education & Foundations</h4>
      <p style="margin: 0 0 5px 0; font-size: 0.95rem;"><strong>Master of Data Science</strong> – Monash University (Final Year candidate)</p>
      <p style="margin: 0 0 15px 0; font-size: 0.95rem; color: #64748b;"><strong>Bachelor of Economics (Statistics Minor)</strong> – St. Xavier’s College [GPA: 7.83/10]</p>
      
      <span style="font-size: 0.8rem; font-weight: bold; color: #64748b; display: block; text-transform: uppercase; margin-bottom: 5px;">Active Certifications:</span>
      <div style="font-size: 0.85rem; color: var(--body-gray);">
        • ArcGIS for Beginners: Mapping Urban Green Spaces (Coursera, 2026)<br>
        • Python Data Analysis Masterclass (2024) | Python Data Visualization Foundations (2020)
      </div>
    </section>

  </div>

  <!-- FOOTER STAMP -->
  <footer style="text-align: center; margin-top: 60px; padding-top: 20px; border-top: 1px solid var(--border-gray); color: #94a3b8; font-size: 0.85rem;">
    Portfolio Pipeline Architecture & Metadata Assets Verified • Compiled June 2026
  </footer>

</div>
