# ICA Picture Decomposition

This project applies **Independent Component Analysis (ICA)** and related subspace methods to images in order to explore how different linear projections reveal internal structure and enable simple segmentations.

## Repository contents

- `ICA.Rmd`  
  Main R Markdown file with all the code and explanations:
  - Construction and whitening of the pixel matrix (stacked RGB channels).  
  - Search for projections that maximize the Fisher index using k-means segmentations.  
  - Visualization of projected images and histograms.  
  - Exploration of orthogonal projections (change of basis).

- `ICA.html`  
  Compiled HTML report generated from `ICA.Rmd`.  

- Image files  
  Example images used throughout the analysis:
  - `Food.JPG`  
  - `Melanoma.jpg`  
  - `pesoni.jpg`  
  - `Test_1.jpg`  
  - `town.jpg`  

  These images are taken from publicly available sources and are included only for academic demonstration.  
  Similar images (e.g., dermatoscopic or natural images) can be easily obtained from public datasets on the Internet and used with the same code.

## Styling

The HTML report uses a custom CSS file named `my-theme.css` to style the output.  
This CSS file is not included in the repository, so to re-render the report you can either:

- Provide your own `my-theme.css`, or  
- Remove or edit the `css: "my-theme.css"` entry in the document header.

