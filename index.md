# Feng Bao

I am a Postdoc working at [Altschuler and Wu lab](https://www.altschulerwulab.org/),  University of California, San Francisco. I obtained my PhD from [Tsinghua University](https://www.tsinghua.edu.cn/en/) in 2019. My research involves general learning approaches and their applications to biological and medical studies as well as drug screens. 

```markdown
Contact: feng.bao with the suffix @ucsf.edu
```

## Research interests

- **Recent focus on statistical learning** 
1. Architectures to disentangle information within multi-modal/-omics inputs 
2. Variational information theoretic methods
3. Constrastive learning for multimodal data 

- **Recent focus on biological questions**
1. Quantify interactions across multiple single-cell modalities
2. Improve throughput of spatially resolved transcriptomics statistically
3. Integrate high-content phenotypic drug profiles

[Full publication list on Google Scholar](https://scholar.google.com/citations?user=I0mcA3MAAAAJ&hl=en)

## Recent works

### In progress
- Integration of high-content imaging-based drug screens.
- Hypioxia multiomics.
- Spatial multiomics.

### **Multi-modality structured embedding for spatially resolved transcriptomics analysis**

Decomposing cell heterogeneity of complex biological systems is an important step to the comprehensive understanding of their organizations and mechanisms. Transcrptomics and imaging are two most widely used approaches to study tissue heterogeneity. Here we try to combine information from these two modalities and provide more extensive dissection of subpopulations in tissues. We follow two principles in design: (1) structured information from single modality (e.g. apparent subpopulations) are preserved after combinations; (2) corrupted information in one modality will not pollute the others. 

[\[Project Page\]](https://github.com/AltschulerWu-Lab/MUSE) [\[Code\]](https://github.com/AltschulerWu-Lab/MUSE) [\[Publication\]](https://doi.org/10.1038/s41587-022-01251-z)

> Characterizing tissue composition through combined analysis of morphologies and transcriptional states. Feng Bao<sup>\*</sup>, Yue Deng<sup>\*</sup>, Sen Wan, Bo Wang, Qionghai Dai<sup>\#</sup>, Steven J. Altschuler<sup>\#</sup>, Lani F. Wu<sup>\#</sup>. Nature Biotechnology. https://doi.org/10.1038/s41587-022-01251-z


### **Deep association kernel learning to explain the genetic causality for complex diseases**

<img style="float: left;" src = "/image/cover.jpeg" width ="200" />
Causal loci contribute to complex diseases in various manners. The comprehensive identification of suspicious genes requires a general genome-wide association study (GWAS) model that can work with different types of genetic effects. Here, we try to use a trainable framework to automatically detect these associated positions meanwhile provide a statistical significance quantification. This work was published as a cover paper in the new Machine Learning Journal of Cell Press [_Patterns_](https://www.sciencedirect.com/journal/patterns/vol/1/issue/6).


[\[Project Page\]](https://github.com/feng-bao-ucsf/DAK) [\[Code\]](https://github.com/feng-bao-ucsf/DAK) [\[Publication\]](https://www.sciencedirect.com/science/article/pii/S2666389920300684)

> Explaining the Genetic Causality for Complex Phenotype via Deep Association Kernel Learning. Bao, Feng, et al. Patterns 1.6 (2020): 100057. 



### **Recurrent neural network for single-cell RNAseq imputations**

scScope is a deep-learning based approach that can accurately and rapidly identify cell-type composition and transcriptional state from noisy single-cell gene-expression profiles containing dropout events and scale to millions of cells. This work was published in _Nature Methods_.

[\[Project Page\]](https://github.com/AltschulerWu-Lab/scScope) [\[Code\]](https://github.com/AltschulerWu-Lab/scScope) [\[Publication\]](https://www.nature.com/articles/s41592-019-0353-7)

<img style="float: left;" src = "/image/scscope.png" width ="500" />
<!-- ![image](/image/scscope.png) -->

> Scalable analysis of cell-type composition from single-cell transcriptomics using deep recurrent learning. Yue Deng\*, Feng Bao\*, Qionghai Dai, Lani F. Wu#, Steven J. Altschuler#, Nature Methods, 2019, DOI: https://doi.org/10.1038/s41592-019-0353-7




### Academic service
Reviewer for the following journals:
- Cell Systems
- Nature Communications
- Genome Biology
- IEEE Transactions on Fuzzy Systems
- IEEE Transactions on Neural Networks and Learning Systems
- Briefings in Bioinformatics
- IEEE Journal of Selected Topics in Signal Processing

_last update: April 1st, 2024_

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-102911962-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-102911962-1');
</script>
