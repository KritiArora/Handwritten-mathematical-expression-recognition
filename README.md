# Handwritten-mathematical-expression-recognition

This project aims to embed Handwritten Mathematical Expressions (HME) directly into a
Docx document. Writing Mathematical Expressions within a WYSIWYG (what you see
is what you get) editor is a cumbersome task which requires a lot of manual effort, which
this paper tries to automate. The task of Recognizing Mathematical Expression is
bifurcated into two sub-tasks i.e. structural analysis and symbol recognition. This project
proposes to use deep learning techniques to do these sub-tasks using an end-to-end
DenseNet based encoder and Attention-Based decoder model, respectively. The model is
trained on CROHME (Competition on Recognition of Online Handwritten Mathematical
Expressions) dataset which consists of InkML files. These InkML files are initially
processed to generate images and MathML from them. We have been successful in
creating docx from HME with accuracy trade-off of 1-2% by significantly reducing
computational complexity than any other WAP based pre-existing techniques.
