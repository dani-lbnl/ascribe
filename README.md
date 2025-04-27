# ASCRIBE VR

<table border="0">
 <tr>
    <td><img src="https://github.com/dani-lbnl/ascribe/blob/main/ascribe4materials.png" width="700">
    </td>
    <td>
     <p>
      Title: ASCRIBE  <a href='https://youtu.be/69CbXve1Jbg'>[video]</a>
      <li> Autonomous Solutions for Computational Research with Immersive Browsing & Exploration
      <li> ASCRIBE-VR is a VR platform offering Autonomous Solutions for Computational Research with Immersive Browsing & Exploration, integrating advanced algorithms with scientific images. ASCRIBE-VR enables multimodal analysis, structural assessments, and immersive visualization, supporting scientific visualization of advanced datasets such as X-ray CT, Magnetic Resonance, synthetic 3D imaging, & much more. Our VR tools are compatible with Meta Quest 3 and 3s and facilitate seamless exploration of large-scale 3D images.
      </td>
 </tr>
</table>

# Microstructure Visualization in Unreal Engine

This repository provides Unreal Engine code specifically developed for the visualization of microstructures. It is designed and optimized for immersive experiences using Meta Quest 3 and Meta Quest 3s. This work is part of the [ASCRIBE project](https://github.com/lbl-camera/ascribe_VR).

## Overview

This repository's main goal is to enable high-quality, real-time visualization of microstructures in virtual reality. The visualization tools allow researchers, engineers, and instructors to explore detailed microstructural models interactively in VR.

## Features

- **Immersive Visualization:** Fully immersive VR interaction tailored specifically for Meta Quest 3 and Quest 3s.
- **High-Resolution Rendering:** Optimized rendering settings for clear visualization of microstructural details.
- **Example Assets:** Includes a collection of mesh examples representing typical microstructures.

## Requirements

- Unreal Engine 5.x
- Meta Quest 3 or Quest 3s headset
- Oculus Link or Air Link setup

## Setup Instructions

1. **Request APK**
2. **Drag it into MetaQuest Developer**
   

## More about the project:

ASCRIBE (Autonomous Solutions for Computational Research with Immersive Browsing & Exploration) is a pioneering research project at the nexus of AI and Extended Reality (XR), designed to revolutionize scientific visualization and accelerate discovery. This initiative aims to develop AI-based algorithms for an integrated platform that leverages multimodal data, structural/chemical analyses, and immersive visualization for interactive exploration. ASCRIBE is uniquely positioned through strategic partnerships with leading centers, including CAMERA, CIWE, and Restor-C, granting access to advanced data sources such as X-ray CT, FIB-SEM, cryo-TEM, time-lapse plant imaging, and simulations, facilitating the creation of digital twins. ASCRIBE is structured around five core functionalities: data filtering, segmentation, quantification, immersion, and interaction. Tailored routines preprocess data to handle noise, anisotropy, and alignment, while AI-based semantic segmentation, steered by Gaussian Processes, enables precise calculation of Volumes of Interest (VOI) and other measurements. Prior-based postprocessing and validation are achieved through AI-driven autonomous loops, providing iterative feedback and uncertainty quantification. For immersive exploration, ASCRIBE develops XR-tools compatible with Meta Quest, powered by Unreal and Godot Engine and adhering to OpenXR standards, allowing ingestion and visualization of raw and reduced data, including VOI-based polygonal meshes and volume renderings. By integrating key technologies such as alignment, anisotropic diffusion, CNNs, viTs, LLMs, VTK, etc., ASCRIBE enhances how we visualize the outcomes of computer vision solutions, exemplified in structural analysis of water electrolyzer membranes. This convergence of AI and XR creates a sense of "presence", enabling researchers to explore complex concepts in virtual environments, accelerating scientific discovery in micro/nanostructure, and materials design.

### Cite this work:
@misc{ushizima2025ascribenewdimensionsscientific,
      title={Ascribe New Dimensions to Scientific Data Visualization with VR}, 
      author={Daniela Ushizima and Guilherme Melo dos Santos and Zineb Sordo and Ronald Pandolfi and Jeffrey Donatelli},
      year={2025},
      eprint={2504.13448},
      archivePrefix={arXiv},
      primaryClass={cs.GR},
      url={https://arxiv.org/abs/2504.13448}, 
}

### Warning
This repo is under active development, so use at your own risk. Found a bug? File an issue or contact [Dani Ushizima](mailto:dani.lbnl@gmail.com)
