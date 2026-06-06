# 3D Interactive ROV Visualization using Python
This repository hosts a proof-of-concept, interactive 3D ROV plot visualized with Plotly from a converted GLB file originally sourced from a STEP CAD file. Optimized specifically for web viewing, it allows you to rotate and inspect the model's complex geometry in your browser.

Github Pages Link: https://maribickpostanes.github.io/ROV-3D/

Note on Viewing: This is a high-resolution export (94.3 MB). For best experience, please view this on a Desktop/Laptop browser. Mobile browsers may struggle with the memory load. It may take a little while to initialize the 3D model, so please be patient while it loads. 

<img width="1920" height="1080" alt="Interactive 3D ROV" src="https://github.com/user-attachments/assets/3a103496-2698-4810-bec2-6feb519368cf" />

## Technical Attribution & Asset Pipeline:
- 3D Model: BlueRobotics BlueROV2 Standard by Rustom Jehangir via GrabCAD
- Data Pipeline: Handled natively via a custom Python script. The original 115 MB STEP file was parsed, processed, and optimized down to a web-ready 65 MB GLB file without reliance on external optimization toolkits.
