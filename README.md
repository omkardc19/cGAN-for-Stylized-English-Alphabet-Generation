# cGAN-for-Stylized-English-Alphabet-Generation
## Conditional Generative Modelling
## Problem Statement
Designing a conditional generative model to generate stylised english alphabets (A-Z) where we 
control which alphabet (eg. R) we want to generate, and style is chosen randomly.
## Input and Output
• Input: A character (A-Z) and a noise vector. You may use one-hot encoding for the character.
• Output: A 36x36 image rendering the given character in a style controlled by the noise vector.
## Dataset
The dataset consists of 26 english alphabets (A-Z) in 66 different fonts

## Assessment Metric
### 1. Style variability:
For a fixed character, different noise vectors should generate different output styles
### 2. Character consistency:
The output image should correspond to the same input character irrespective of the noise vector
### 3. Style consistency:
For a fixed noise vector, all characters generated should have the same style
