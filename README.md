<p align="center" width="100%">
  <img alt="Logo" width="33%" src="Logos/logo.png">
</p>

<h1 align="center">Tessera Badge</h1>

<p align="center" width="100%">
  <a href="https://github.com/AntonioMR/tessera-hw/actions/workflows/ci.yaml">
    <img alt="CI Badge" src="https://github.com/AntonioMR/tessera-hw/actions/workflows/ci.yaml/badge.svg?branch=">
  </a>
</p>

<p align="center" width="100%">
    <img src="Images/dummy_image.png">
</p>

***

<p align="center">
  <img alt="3D Top Angled" src="Images/tessera-angled_top.png" width="45%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="3D Bottom Angled" src="Images/tessera-angled_bottom.png" width="45%">
</p>

***

## SPECIFICATIONS

| Parameter | Value | 
| --- | --- |
| Dimensions | 54.0 × 85.61 mm |

***

## DIRECTORY STRUCTURE

    .
    ├─ Computations       # Misc calculations
    ├─ HTML               # HTML files for generated webpage
    ├─ Images             # Pictures and renders
    │
    ├─ kibot_resources    # External resources for KiBot
    │  ├─ colors          # Color theme for KiCad
    │  ├─ fonts           # Fonts used in the project
    │  ├─ scripts         # External scripts used with KiBot
    │  └─ templates       # Templates for KiBot generated reports
    │
    ├─ kibot_yaml         # KiBot YAML config files
    ├─ KiRI               # KiRI (PCB diff viewer) files
    │
    ├─ lib                # KiCad footprint and symbol libraries
    │  ├─ lib_fp          # Footprint libraries
    │  ├─ lib_packages3d  # Component 3D models
    │  └─ lib_sym         # Symbol libraries
    │
    ├─ Logos              # Logos
    │
    ├─ Manufacturing      # Assembly and fabrication documents
    │  ├─ Assembly        # Assembly documents (BoM, pos, notes)
    │  │
    │  └─ Fabrication     # Fabrication documents (ZIP, notes)
    │     ├─ Drill Tables # CSV drill tables
    │     └─ Gerbers      # Gerbers
    │
    ├─ Report             # Reports for ERC/DRC
    ├─ Schematic          # PDF of schematic
    ├─ Templates          # Title block templates
    ├─ Testing
    │  └─ Testpoints      # Testpoints tables      
    │
    └─ Variants           # Outputs for assembly variants
