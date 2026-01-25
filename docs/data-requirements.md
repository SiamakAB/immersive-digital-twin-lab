# Data Requirements for Immersive XR Demonstrations

*This document outlines the preferred data types and formats for use in the **Immersive Digital Twin Lab** at the University of Oulu. These datasets will enable accurate 3D modeling, VR demonstrations, and interactive exploration of supersites and use cases within the DIWA XR environment. This page is a draft and subject to updates. Feedback is welcome.*

---

## Overview

The **DIWA XR Lobby** is being developed to provide an **immersive, interactive, and visually intuitive environment** for demonstrating selected supersites and real-world use cases.  
High-quality VR demonstrations rely on consistent, accurate, and complete datasets, enabling 3D visualization, time-based analysis, and scenario exploration of water infrastructure and environmental processes.

To support this, we kindly request contributions from DIWA *researchers/partners* following the data guidelines below.

---

## Requested Data Types

### 1. Base Spatial Data
- Study area boundaries (polygons)  
- Existing infrastructure layers (rivers, lakes, dams, channels, pumping stations, reservoirs)  
- Optional roads or access paths  
- Elevation or terrain data (DEM/DSM or point clouds)  

**Preferred formats:** Shapefile, GeoJSON, KML, GeoTIFF, LAS/LAZ  
**Coordinate system:** WGS84 / EPSG:4326 preferred

---

### 2. Thematic and Monitoring Data
- Sensor locations with measured variables (flow, turbidity, temperature)  
- Environmental monitoring points (water quality, groundwater levels)  
- Event or intervention locations (floods, incidents, maintenance activities)  

**Preferred formats:** Shapefile, GeoJSON, CSV, JSON  
**Additional info:** Include timestamps, units, sensor or event descriptions

---

### 3. Temporal / Time-Series Data
- Historical measurements  
- Scenario or “what-if” intervention timelines  

**Preferred formats:** CSV, JSON, or GIS layers with time attributes

---

### 4. 3D Assets and Models
- 3D models of infrastructure (pumps, treatment plants, bridges, buildings)  
- Textures or materials (if available)  

**Preferred formats:** FBX, OBJ, glTF / GLB

---

### 5. SfM / Reality Capture Data
- Photogrammetric models derived from drone or camera imagery  
- Point clouds, textured meshes, or orthophotos representing real site conditions  

**Preferred formats:** LAS/LAZ (point clouds), OBJ/FBX (meshes), orthophotos  

*These datasets are particularly valuable for high-fidelity VR visualization of supersites.*

---

### 6. Metadata and Supporting Materials
- Feature IDs, names, types, operational status  
- Measurement units and data source information  
- Optional site photos, annotations, reports, or documentation links

---

## Submission and Coordination

To streamline data sharing:

1. **DIWA XR Data Request Table**  
   - Please complete the table for each relevant supersite/use case.  
   - Submit it along with corresponding files or cloud links.

2. **Submission Options**  
   - **DIWA DataLab:** Upload datasets, 3D models, and related files to the collaborative cloud workspace on CSC Rahti infrastructure.  
   - **Email submission:** Send completed materials directly to `siamak.bazzaz@oulu.fi`.

*Your contributions are essential for creating accurate, meaningful, and immersive XR demonstrations.* 

---

⚠️ ***Note:** This page is under construction. Updates and clarifications will be provided as the Immersive Digital Twin Lab develops. Feedback, suggestions, and questions are highly appreciated.*

