# Introduction

This thesis focuses on epigenome-wide association studies (EWAS), which assess the association between DNA methylation changes throughout the genome and traits of interest. Advances in technology and an increasing number of samples has lead to hundreds of EWAS having been performed to date (REFERENCE EWAS CATALOG CHAPTER). Goals of these EWAS included using DNA methtlation marks as predictors, diagnostic factors, and modifiable mediators of traits. 

To help inform design of future studies, there is a need to understand what has been discovered thus far in EWAS and what future EWAS are likely to add in the context of current EWAS and other study designs. Further, to improve biological inference of sites identified in EWAS, causality (or lack of) should be established. IS THIS TOO VAGUE?

NON-VAGUE THING TO SAY -- read over both and decide what to add:
- Key things which are not currently understood:
- Why certain DNA methylation sites/regions of the genome are more prevalent in EWAS to date
- How much trait variation DNA methylation tends to associate with 
- Whether EWAS can add to current biological understanding in addition to other study designs
- Whether DNA methylation-trait associations in EWAS are causal

In this chapter I describe DNA methylation in context of the regulatory processes in human cells, discuss it's potential for use in population level research and describe the current state of EWAS research. Then I discuss how epigenetic-epidemiologists can draw on the methods developed by their genetics counter-parts to 1. understand what information has been gained from EWAS, 2. understand what information is left to gain from EWAS and 3. understand the causal nature of DNA methylation-trait associations identified in EWAS.


## DNA methylation as part of the regulome
The research questions of this thesis pertain to a specific study type, EWAS, of a specific epigenetic mark, DNA methylation. DNA methylation is one of many epigenetic marks that are involved in gene regulation (the regulome), so here I briefly outline some of these regulatory marks and discuss DNA methylation in the context of this complex biological process.

### The regulome
Gene expression is a tightly controlled process and only in the right circumstances will RNA polymerase II be able to bind the correct site, initiate and finally complete the transcription process (REFS). The importance of this level of control is no more apparent than in the developmental stages of human life. Humans start as a single cell and after roughly nine months are transformed into a multicellular organism with trillions of cells, including 100s of unique cell types (REF). As these cells arise from a single progenitor they must contain identical genetic sequences (bar a few somatic mutations). Therefore, the process by which the body is able to create such diversely functioning cells and tissues must come from regulation of how the genetic sequence is read and its products (REFs). Indeed it was in developmental biology that we first began to understand the processes that may regulate gene expression (REFs). There are a plethora of methods cells use to regulate gene and protein expression post-transcriptionally (REFs), but these are beyond the scope of this thesis. So I'll continue to describe the regulome just in the context of epigenetic marks.

### Defining epigenetics
The definition of epigenetics is much debated amongst those who study cellular and molecular processes (REFs). Waddington first coined the term and he originally defined it as __X__ (REF). To avoid confusion, throughout the rest of the thesis, here is what I mean when using the term __epigenetics__: the study of mitotically heritable changes in gene expression that occur without changes in DNA sequence. When referring to __epigenetic marks__ I simply mean chemical changes to the genome and genome-bound proteins that are mitotically heritable and may influence gene expression without changing the DNA sequence. 

### Histone modifications 
Histones are genome-bound proteins composed of four subgroups that are present twice each in a single histone octamer. Modifications can occur to any of the histone monomers and these have been associated with both positive and negative changes in gene expression (REFs). Histone modifications are numerous and complex in nature. To briefly describe the complexity, there are at least __X__ types of histone modifications, each of the histone monomers can be modified across many different sites, and for any one site mutiple of the same modification can occur and it is the combination of all of this that plays a role in gene expression regulation (REFs). Furthermore, histone modifications are subject to rapid change upon environmental stimulus to help induce or repress gene expression (REFs). This has meant, that for only a few histone marks are we certain of the role (REFs) and that taking a snapshot of the histone modifications present in cells may give a poor summary of how gene regulation is occuring. Very few population-based studies have assessed histone modifications because of these, plus some other technical difficulties (REFs). They may become far more prominent in the future as our understanding and ability to measure the modifications in a meaningful way increases. 

### DNA methylation
Good review: Peter Jones 2012
DNA methylation is the addition of a methyl group to the DNA, which primarily occurs at the 5' cytosine of a CpG site. Little is known about the role of non-CpG site DNA methylation and current EWAS only measure CpG methylation, so that will be my focus here. The function of this epigenetic mark was proposed back in 1975 (REFs), where two papers suggested it represses gene expression and ever since then many papers have shown the correlation between DNA methylations around genes and a reduction in expression of those genes. Unfortunately, it's not that simple and even now the role of DNA methylation is being debated, with a paper recently suggesting that any DNA methylation changes associated with changes in gene expression were just a by-product of other regulatory processes such as transcription factor binding (REF). Regardless, DNA methylation is closely linked with genomic function and correlates with various aspects in different ways (__FIGURE__). 

CpG sites are not randomly distributed throughout the genome, but are often found in clusters and so if DNA methylation does have an effect on things like gene expression it's thought that methylation and de-methylation of CpG sites in groups is what drives their regulatory function. To support this, there are clear biological processes that regulate DNA methylation at nearby sites together, for example, CpG sites at transcription factor binding sites will be de-methylated as a group when the transcription factor binds (REF), and further nearby sites are often statistically correlated. However, there is no evidence to suggest that neighbouring sites do indeed act in tandem or whether it is likely one site from the group driving regulatory function. This is something I explore a little more in (REFERENCE h2ewas CHAPTER!).  

One major difference between DNA methylation and other epigenetic marks, that was alluded to earlier, is that DNA methylation is far more stable. Enzymes do exist that can actively demethylate the DNA, for example the ten-eleven translocation (TET) enzymes, but ultimately cell division is required for full demethylation of a DNA molecule. Biologically, this suggests DNA methylation might be involved in long-term repression of gene expression, which can be seen for X-inactivation, and practically it makes studying the epigenetic mark easier as it prevents large temporal variations in DNA methylation (though they may occur!), so fewer samples are needed.

Figure here: 

Figure should contain these diagrams:
1. DNA methylation at TSS and no DNA methylation in gene body (repressed transcription)
2. No DNA methylation at TSS and DNA methylation in gene body (active transcription)
3. DNA methylation in centromeres
4. DNA methylation at transposable elements


## Use of DNA methylation in a population setting {#dnam-phs}

The relationship between a large number of traits and DNA methylation have now been studied, from childhood adversities (REFs) to smoking (REFs), and one of the appealing factors of doing this research is that DNA methylation is modifiable. Thus, in theory, negative effects of something like childhood adversity may be captured in DNA methylation and could potentially be, in part, reversed by altering the methylome in some way. This view that clinicians may soon have the power to do anything like this has likely lead to a lot of poor and inconsequential EWAS being published. Unfortunately, there are massive complications to this research. Firstly, it should be recognised that DNA methylation has the same undesirable properties of every other complex phenotype, it correlates with a lot of things, making any associations suceptible to confounding and reverse causation, so determining causality is tricky (this will be discussed in \@ref(genetics-in-ewas)). Secondly, current methods used to modify DNA methylation mostly rely on broad remodelling of the DNA methylome (e.g. 5-AZA), which is completely unviable in a clinical setting. Granted, there are methods that can be used to increase specificity of targetting DNA methylation changes in the genome (REFs), but I'd wager these are far from being used in the clinic, which leads onto the last point. Finally, DNA methylation varies between tissue and cell types. Not only does pose the issue of confounding when pooling cell types from a tissue, it also leads to large complexities in the interpretation of DNA methylation studies. Most studies are conducted in readily available tissues, such as blood and saliva, for obvious reasons, but there is no way of knowing which tissue is best suited for studying DNA methylation for many complex traits. DNA methylation does correlate between tissues (REFs), which may mean a readily available tissue can act as a surrogate, but this also means targeting DNA methylation in the tissue measured for the EWAS, may have no impact on your phenotype. All together these problems mean that establishing causality is difficult, then targeting specific DNA methylation sites of interest to effect change is also challenging (and untested in humans), and finally the tissue that needs to be targetted may be impossible to target anyway.

Despite all this, I still believe there are uses to conduct EWAS, just more care is needed when designing and interpreting EWAS. 

* Describe DNA methylation as similar to other phenotypes 
* Describe how DNA methylation can be used in the context of prediction and diagnosis 
* Describe how DNA methylation can (or maybe can't) be targeted for treatments 

## EWAS

* Describe what an EWAS is and explain how it is conducted 
* Describe the current successes that have come from EWAS 
* Describe the current problems with EWAS

## Using methods from genetics to help inform future EWAS {#genetics-in-ewas}

__Might be an idea to add detail of some of these methods into appendices (e.g. mathematical basis of snp-heritability)__

* Give a little intro on what problems this chapter focuses on
* Describe the GWAS catalog and what it has done for genetic epi and how this can be adapted for EWAS
* Describe and explain heritability (and how it can be applied to EWAS)
* Describe pathway analysis??
* Describe MR


## Overview of thesis aims

__BELOW IS TERRIBLE BUT HELPFUL AS IT GIVES STRUCTURE__

EWAS might be an effective study technique to help provide biomarkers for better diagnosis, prognosis and prediction of disease and traits and further it could provide insight into trait aetiology as well as the downstream effects of a trait. However, with the field in it's infancy, there has yet to be a comprehensive look at what information has been gained from EWAS, what information is still to gain from EWAS in it's current state and whether or not the sites identified in EWAS are likely to be causally related to traits. 

In Chapter 3 the aim is to produce a database that brings together all the information currently published (as of X-date) together along with new EWAS with full summary statistics. This vast database will then be explored in Chapter 4, giving a detailed picture of what sites throughout the genome have been discovered in EWAS and exploring why they might have been discovered. NEED TO ADD IN HOW!

After exploring the information already gained from EWAS, Chapter 5 explores the amount of information still to gain from EWAS. NEED TO ADD IN HOW!

The database from Chapter 3 will again be used to extract large EWAS datasets for Chapter 6, where potential biological information from these EWAS will be compared to that of GWAS from the same traits. NEED TO ADD IN HOW!

Finally as an initial means of assessing whether DNA methylation might be causally associated with traits of interest, Chapter 7 will aim to use MR to help infer if DNA methylation identified in EWAS of lung cancer are likely to be causing lung cancer.