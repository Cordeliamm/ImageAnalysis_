# ImageAnalysis
This repository is a part of my bachelor thesis image analysis, exploring how linguistic framing in prompt engineering influences biases in AI-generated images.

**Bias Mitigation Prompting: A Framework for Inclusive Text-to-Image Generation**

This project investigates how prompt engineering using neutral, inclusive and counter-stereotypical language influence the representation of different age, gender and race/ethnicity groups in AI-generated images with different Text-to-Image models. 

Methodology:
- The models used to generate images were DALLE-3, Adobe Firefly, MidJourney, Leonardo, and Stable Diffusion;
- The facial attributes (age, gender, race/ethnicity) were extracted and analysed using [DeepFace](https://github.com/serengil/deepface);
- For statistical analysis, Kruskal-Wallis and Chi-Square tests were applied; 
- Visualisations were created using matplotlib and seaborn.
