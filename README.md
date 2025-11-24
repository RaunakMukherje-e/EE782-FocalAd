# FOCAL Ad

## Summary
This project adapts the FOCAL factorized latent-space framework to image–text advertising data. Using pretrained ResNet-18 and BERT features, each modality is mapped into a **shared** semantic space and a **private** modality-specific space, enforced via contrastive similarity and orthogonality losses. 
Flickr8k is used as a proxy ad-creative dataset, and a synthetic conversion label is generated through a hidden linear mapping to enable downstream evaluation. With only lightweight MLP encoders trained (feature extractors frozen), the model’s shared representation achieves strong semantic alignment, while full (shared+private) embeddings deliver the best conversion-prediction accuracy (~67%). The approach demonstrates that disentangled multimodal embeddings can serve as robust inputs for simple downstream classifiers.

Full report: `focalad_report_22b3955_22b1215_22b1829.pdf`

Video link: https://drive.google.com/file/d/17stTA_IWKLAFIfZPSoOpMOx8zXFjtA-4/view?usp=sharing
