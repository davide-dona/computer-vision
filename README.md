# Computer Vision
A detailed collection of LaTeX-based lecture notes for the Computer Vision course at the University of Trento, academic year 2025/2026, instructed by Prof. Nicola Conci.

<div align="center">
    <a href="main.pdf">
        <img src="media/preview.png" alt="Notes Preview" width="300px">
    </a>
    <br>
    <a href="main.pdf" style="display: block; margin-top: 10px; font-size: 15px; font-weight: bold; color: #007acc;">
    Download the PDF notes</a>
</div>

---

## Topics Covered

| # | Section | Description |
|---|---|---|
| 1 | [Images and Videos](chapters/01_image-videos.tex) | The imaging pipeline: acquisition, digitization, color representation, and video basics. |
| 2 | [Image Elaboration and Feature Extraction](chapters/02_elaboration.tex) | Histograms, spatial filtering and convolution, and morphological filters. |
| 3 | [Models](chapters/03_models.tex) | Pinhole camera model, lenses, projection, and illumination. |
| 4 | [Motion Detection](chapters/04_motion-detection.tex) | Optical flow, its challenges, and motion detection in practice. |
| 5 | [Motion Tracking](chapters/05_tracking.tex) | Detection and association, region- and feature-based tracking, Lucas–Kanade, and Bayesian tracking. |
| 6 | [Camera Geometry](chapters/06_geometry.tex) | Affine transformations, 2D/3D camera matrices, binocular stereo, and multi-view geometry. |
| 7 | [Local Feature Extraction](chapters/07_feature_extraction.tex) | Histogram of Oriented Gradients (HOG), feature compression, and SIFT. |
| 8 | [Classification](chapters/08_classification.tex) | The Viola–Jones object detection framework. |
| 9 | [3D Scene Reconstruction](chapters/09_structure.tex) | Structure from Motion (SfM), SLAM, and how they compare. |

---

##  Contributing

Contributions are welcome! Here's how you can help:

###  Issues
- Found a **typo**, a **wrong formula**, or a **missing topic**? [Open an issue](../../issues/new).
- Please include the **section name** and **page number** (if applicable).

###  Pull Requests
1. **Fork** this repository.
2. Create a new branch: `git checkout -b fix/your-description`.
3. Make your changes (edit the `.tex` files under `chapters/`).
4. Make sure the project **compiles without errors**: `latexmk -pdf main.tex`.
5. **Commit** with a descriptive message and **push** your branch.
6. Open a **Pull Request** against `main`.

---

## License

This project is intended for educational purposes. Feel free to use and share the notes with proper attribution.