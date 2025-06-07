# medical-Image-Segmentation-dspc

## Unsupervised Nuclei Phenotyping in H&E-Stained Histopathology Images

This project presents a three-phase **unsupervised clustering** for segmenting and phenotyping nuclei in H&E-stained histopathology images, using:

- **Superpixel clustering** (SLIC + KMeans/FCM/GMM)
- **Pixel-level clustering**
- **Stain-based clustering** on the Hematoxylin channel

We use the **MoNuSeg 2018** dataset with expert-annotated masks and evaluate our method using instance-level metrics (TP, FP, FN).

Best results are achieved using Hematoxylin-based clustering, with improved nuclei separation and minimal annotation dependency.

---

## 📌 Research Poster

![Research Poster](./DSPC_Poster.jpg)

> *(If the poster doesn’t render, click [here to view it](./DSPC_Poster.pdf).)*

---

## References

- Kumar et al. (2019). *Multi-Organ Nuclei Segmentation Challenge (MoNuSeg)*. IEEE TMI.  
- Macenko et al. (2009). *Histology slide normalisation*. ISBI.  
- Bishop, C. M. (2006). *Pattern Recognition and Machine Learning*. Springer.

