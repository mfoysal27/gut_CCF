# 3D Tissue Visualizer

## Overview
This repository contains 3D STL models of gut tissue layers created from AI-annotated gut tissue images in 2D. These models represent different anatomical structures of the gastrointestinal tract in high detail.

## Tissue Layer Organization
The following diagram shows the hierarchical organization of the tissue layers represented in the STL files:

```mermaid

    "Villi": (255, 192, 203),  # Pink
    "Glands": (255, 255, 255),  # White
    "Submucosa_Ganglion": (64, 64, 64),  # Dark gray
    "Submucosa_Fiber_tract": (192, 192, 192),  # Light gray
    "Submucosa_Submucosal_blood_Vessel": (128, 0, 128),  # Purple
    "Submucosa_Interstitial_tissue": (0, 0, 128),  # Navy Blue
    "Circular_muscle": (0, 128, 128),  # Teal
    "Myenteric_Ganglion": (205, 133, 63),  # Brown
    "Myenteric_Fiber_tract": (101, 67, 33),  # Dark brown
    "Longitudinal_muscle": (255, 165, 0),  # Orange
    "Others_Out_of_Tissue": (0, 0, 0),  # Black
    "Others_Lymphoid_tissue": (196, 162, 196),  # Light purple
    "Others_Vessel": (75, 0, 130),  # Indigo

    
```

## Visualization Tools
A web-based visualization tool as well as a desktop visualization tool are available at:

GitHub Repository: [https://github.com/mfoysal27/tool_3d_viewer](https://github.com/mfoysal27/tool_3d_viewer)

## STL File Details

| File Name | Size | Description |
|-----------|------|-------------|
| Circular_muscle.stl | 80 MB | 3D model of the circular muscle layer of the gut wall, which is responsible for constriction and peristaltic movements. |
| Longitudinal_muscle.stl | 82 MB | 3D model of the longitudinal muscle layer, which runs along the length of the gut and works with circular muscles for motility. |
| Myenteric_Fiber_tract.stl | 9.2 MB | Neural fiber tracts in the myenteric plexus, which is located between the circular and longitudinal muscle layers. |
| Myenteric_Ganglion.stl | 7.5 MB | Ganglia (clusters of nerve cell bodies) in the myenteric plexus, controlling gut motility. |
| Submucosa_Fiber_tract.stl | 528 KB | Neural fiber tracts in the submucosal plexus, located in the submucosa layer. |
| Submucosa_Ganglion.stl | 2.7 MB | Ganglia in the submucosal plexus, regulating secretion and local blood flow. |
| Submucosa_Interstitial_tissue.stl | 61 MB | Connective tissue in the submucosa layer that supports the mucosa and contains blood vessels, lymphatics, and nerves. |
| Glands.stl | 89 MB | Secretory glands in the gut wall that produce digestive enzymes and mucus. |
| Villi.stl | 181 MB | Finger-like projections in the small intestine that increase surface area for absorption. |
| Others_Lymphoid_tissue.stl | 528 KB | Lymphoid tissue in the gut wall, part of the gut-associated lymphoid tissue (GALT) immune system. |
| Others_Out_of_Tissue.stl | 174 MB | Structures outside the main tissue layers or artifacts from the annotation process. |

## Usage Instructions

### Viewing STL Files
1. **Online Viewer**: Use the web-based tool at the GitHub repository linked above.
2. **Desktop Application**: Download the desktop application from the same repository for more advanced visualization options.
3. **Other Software**: These STL files can also be viewed in standard 3D software like:
   - [Blender](https://www.blender.org/) (free, open-source)
   - [MeshLab](https://www.meshlab.net/) (free, open-source)
   - [Autodesk Viewer](https://viewer.autodesk.com/) (free online viewer)
   - [ParaView](https://www.paraview.org/) (free, open-source)

### Tips for Large Files
Some of these STL files are quite large (>100 MB). For optimal performance:
- Use a computer with sufficient RAM (16+ GB recommended)
- Consider decimating the meshes if experiencing performance issues
- For web viewing, ensure you have a stable internet connection

## Research Context
These 3D models were generated from AI-annotated histological images of gut tissue. They represent different anatomical structures and can be used for educational purposes, research visualization, or as reference models for further analysis.

## License
Please refer to the repository license for usage rights and restrictions.

