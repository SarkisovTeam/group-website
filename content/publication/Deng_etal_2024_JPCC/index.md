---
title: "Engineering Machine Learning Features to Predict Adsorption of Carbon Dioxide and Nitrogen in Metal–Organic Frameworks"
authors:
  - Zijun Deng
  - admin
date: '2025-06-05T00:00:00Z'
doi: '10.1021/acs.jpcc.4c01692'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-06-05T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: '*J. Phys. Chem. C*'
publication_short: ''

abstract: In this article, we propose simple, interpretable machine learning (ML) features aimed at improving the accuracy of ML models in predicting adsorption of gases, such as methane, ethane, propane, krypton, and xenon, in metal–organic frameworks (MOFs). In particular, we introduce energy-based features that incorporate surface energy histograms and radial distribution functions. These features effectively capture spatial variations in interaction energy, thereby improving the predictive capabilities of the ML models. We further extend this approach to predict the adsorption of carbon dioxide and nitrogen in a diverse set of MOFs under ambient conditions by including the Coulombic energy component in the proposed energy-based features. The final ML model combines the energy-based features with geometric characteristics of MOFs and Henry’s law constants. This integration results in significantly increased predictive accuracy of the models, especially within the moderate pressure regime, when compared to that of previous studies. Using the CoRE MOF database for training and testing, our ML model achieves a prediction accuracy of R2 > 0.96 for methane, ethane, krypton, and xenon at various conditions, R2 > 0.96 for propane, R2 > 0.80 for carbon dioxide, and R2 > 0.97 for nitrogen. Using the CRAFTED database of simulated adsorption isotherms for carbon dioxide and nitrogen, we demonstrate the robustness of the ML model in predicting single-component isotherms at a specific temperature. In this test, the model achieves R2 > 0.87 for carbon dioxide and R2 > 0.90 for nitrogen. The physics-based nature of the proposed features allows us to provide some interpretation of why the predictions of the ML model are better for some materials than for others. According to this interpretation, an accurate representation of the shape of the potential energy surface plays an important role in capturing the process of adsorption. Finally, we acknowledge certain limitations of the current model such as the oversimplification in representing the geometry and interactions of molecules with polar interactions.
featured: false

# links:
# - name: ""
#   url: ""
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
