# SPeDaC
The resource has been evaluated in: G. Gambarelli, A. Gangemi and R. Tripodi, "Is Your Model Sensitive? SPEDAC: A New Resource for the Automatic Classification of Sensitive Personal Data," in IEEE Access, vol. 11, pp. 10864-10880, 2023, doi: 10.1109/ACCESS.2023.3240089.

If you use SPeDaC1 or SPeDaC2, please reference this work in your paper:

```
@ARTICLE{10031607,
  author={Gambarelli, Gaia and Gangemi, Aldo and Tripodi, Rocco},
  journal={IEEE Access}, 
  title={Is Your Model Sensitive? SPEDAC: A New Resource for the Automatic Classification of Sensitive Personal Data}, 
  year={2023},
  volume={11},
  number={},
  pages={10864-10880},
  doi={10.1109/ACCESS.2023.3240089}}
```

If you use SPeDaC3, please reference this work in your paper:

```
@Article{bdcc6030090,
  AUTHOR = {Gambarelli, Gaia and Gangemi, Aldo},
  TITLE = {PRIVAFRAME: A Frame-Based Knowledge Graph for Sensitive Personal Data},
  JOURNAL = {Big Data and Cognitive Computing},
  VOLUME = {6},
  YEAR = {2022},
  NUMBER = {3},
  ARTICLE-NUMBER = {90},
  URL = {https://www.mdpi.com/2504-2289/6/3/90},
  ISSN = {2504-2289},
  DOI = {10.3390/bdcc6030090}
}
```

## Instructions for downloading the SPeDaC corpora

To download the datasets you have to sign an agreement of ethical research purposes. You can find the agreement doc in this repository.

Once the corresponding license agreement is signed, you have to send it to the authors at: gaiagambarelli@gmail.com .

Subject: [SPeDaC download]

Body: Your name, e-mail, telephone number, organization, postal mail, purpose for which you will use the dataset, time and date at which you sent the email with the signed license agreement.

Attachments: the document of agreement signed for the parts of the licensee.

Once the email copy of the license agreement has been received, you will receive the SPeDaC corpora.

For additional informations, please contact the authors.


## SPeDaC-corpora

The first dataset (SPeDaC1) concerns sensitive and non sensitive sentences. The second one (SPeDaC2) represents personal data categories (PDCs) from DPV-PD (https://w3c.github.io/dpv/dpv-pd/) classifying it with 5 macro-categories labels (SpecialData, Financial&Tracking, Internal, External and Social). Every corpus is splitted into training, validation and test set, in order to compare the experimental results we have previously achieved with future results.

<img width="279" alt="corpora" src="https://user-images.githubusercontent.com/65297512/171263023-81cfaa88-2689-426c-8ec2-e5fc02c926fa.PNG">

In SPeDaC2 you can find also a fine-grained dataset of 5562 sentences labeled with the 74 personal data categories.

The annotations are sentence-level and in WebAnno TSV v3.3 format.

SPeDaC3 and SPeDaC4 are evolutions of the resource, moving from binary and macro-category classification toward fine-grained annotation of personal data aligned with the W3C Data Privacy Vocabulary Personal Data module (DPV-PD, https://w3c.github.io/dpv/dpv-pd/).

The third dataset (SPeDaC3) extends the annotation of the same corpus with 61 fine-grained personal data categories derived from DPV-PD, including age, occupation, location, health conditions, mental health, family relations, political beliefs, preferences, financial status, and physical characteristics. As in previous versions, the annotations remain sentence-level and in WebAnno TSV v3.3 format.

The fourth dataset (SPeDaC4) re-annotates the SPeDaC corpus at span-level, marking the exact text spans carrying sensitive personal data rather than labeling entire sentences. This shift from sentence classification to span extraction enables fine-grained extraction tasks that more accurately reflect the distribution of privacy-sensitive content within each textual unit. The category set has been enriched through a systematic alignment with DPV-PD version 2.2, which underwent significant structural changes between 2023 and 2024; the analysis identified one new category — Citizenship — not subsumed by existing SPeDaC labels, bringing the total to 62 fine-grained personal data categories. SPeDaC4 also introduces an Italian-language translation of the corpus, representing the first multilingual extension of SPeDaC. Annotation was completed in 2026 using the INCEpTION platform. The annotations are span-level and in WebAnno TSV v3.3 format.
