# Awesome Healthcare Datasets

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome healthcare datasets for machine learning, research, and exploration.

## Contents

- [Clinical Data](#clinical-data)
  - [General EHR/ICU Data](#general-ehricu-data)
  - [Specific Conditions/Cohorts](#specific-conditionscohorts)
  - [Clinical Notes/Text](#clinical-notestext)
  - [Waveform Data](#waveform-data)
  - [Prescription Data](#prescription-data)
- [Imaging Data](#imaging-data)
  - [Radiology (X-ray, CT, MRI)](#radiology-x-ray-ct-mri)
  - [Ophthalmology](#ophthalmology)
  - [Dermatology](#dermatology)
  - [Pathology](#pathology)
  - [Microscopy](#microscopy)
  - [Dental](#dental)
  - [Other Imaging Modalities](#other-imaging-modalities)
- [Omics Data](#omics-data)
  - [Genomics](#genomics)
  - [Transcriptomics](#transcriptomics)
  - [Proteomics](#proteomics)
  - [Metabolomics](#metabolomics)
  - [Multi-omics](#multi-omics)
  - [Pharmacogenomics](#pharmacogenomics)
- [Biomedical Knowledge Graphs and Ontologies](#biomedical-knowledge-graphs-and-ontologies)
  - [General Medical Terminologies](#general-medical-terminologies)
  - [Drug and Chemical Information](#drug-and-chemical-information)
  - [Disease and Gene Information](#disease-and-gene-information)
  - [Pathway and Interaction Databases](#pathway-and-interaction-databases)
- [Public Health Data](#public-health-data)
  - [Global Health](#global-health)
  - [US-Specific Public Health](#us-specific-public-health)
  - [Health Systems and Policy](#health-systems-and-policy)
- [Biomedical Literature](#biomedical-literature)
  - [Article Databases and Collections](#article-databases-and-collections)
  - [Literature-Based Datasets](#literature-based-datasets)
- [Wearable and Sensor Data](#wearable-and-sensor-data)
- [Social Determinants of Health (SDOH)](#social-determinants-of-health-sdoh)
- [Synthetic Data](#synthetic-data)
- [Miscellaneous](#miscellaneous)
- [Contribute](#contribute)
- [License](#license)

## Clinical Data

### General EHR/ICU Data

1.  [MIMIC-III Clinical Database](https://physionet.org/content/mimiciii/1.4/) - Deidentified health data from ~40,000 critical care patients.  *Requires data use agreement and training.*
2.  [MIMIC-IV](https://physionet.org/content/mimiciv/2.2/) - Updated MIMIC-III, 2008-2019. *Requires data use agreement and training.*
3.  [eICU Collaborative Research Database](https://physionet.org/content/eicu-crd/2.0/) - Multi-center ICU data from across the US. *Requires data use agreement and training.*
4.  [AmsterdamUMCdb](https://amsterdammedicaldatascience.nl) - Deidentified health data from Amsterdam University Medical Center.
5.  [HiRID](https://physionet.org/content/hirid/1.1.1/) - High time-resolution ICU data from Bern University Hospital, Switzerland (Inselspital). *Requires Credentialed Access*.
6.   [Medical Information Mart for Intensive Care (MIMIC) - IV Emergency Department (MIMIC-IV-ED)](https://physionet.org/content/mimic-iv-ed/2.2/)
7.  [BH-CHPR, Beth Israel](https://github.com/BH-CHPR/Emergency-Department-Visit-Classification) -  Emergency department visit data with classification labels, focus on reducing ED utilization.

### Specific Conditions/Cohorts

1. [MIMIC-IV-ED](https://physionet.org/content/mimic-iv-ed/2.2/) - Emergency department data from MIMIC-IV. *Requires data use agreement and training.*
2.  [AMR-UTI](https://physionet.org/content/antimicrobial-resistance-uti/1.0.0/) - Antimicrobial Resistance in Urinary Tract Infections.
3.  [Abdominal and Direct Fetal ECG Database](https://physionet.org/content/adfecgdb/) - Multichannel fetal ECG recordings.
4.  [The Pediatric Epilepsy Research Consortium (PERC) Data](https://www.pediatriced.org/) - Data from multicenter observational studies on children with epilepsy. (Contact PERC for access)
5.  [Nationwide Emergency Department Sample (NEDS)](https://www.hcup-us.ahrq.gov/nedsoverview.jsp) - Large, publicly-available all-payer ED database (US). *Available for purchase.*
6. [National Emergency Department Samples](https://www.hcup-us.ahrq.gov/db/nation/neds/nedsdbdocumentation.jsp) - The Healthcare Cost and Utilization Project.

### Clinical Notes/Text

1.  [MIMIC-IV-Note](https://physionet.org/content/mimic-iv-note/2.2/) - Deidentified clinical notes from MIMIC-IV.  *Requires data use agreement and training.*
2.  [i2b2/n2c2 NLP Research Data Sets](https://www.i2b2.org/NLP/DataSets/) - Several datasets of deidentified clinical notes with annotations for various NLP tasks (e.g., de-identification, relation extraction). *Requires data use agreement.*
3. [mtsamples](https://www.mtsamples.com/) - A large collection of transcribed medical sample reports.
4.  [THYME corpus](https://github.com/thராஜ்/temporal_hindi) - clinical notes with temporal annotations. Contains colon cancer, brain tumor and epilepsy corpus.

### Waveform Data

1.  [MIMIC-III Waveform Database](https://physionet.org/content/mimic3wdb/1.0/) - Waveform data matched to MIMIC-III. *Requires data use agreement and training.*
2.   [MIMIC-IV Waveform Database Matched Subset](https://physionet.org/content/mimic4wdb-matched/0.1.0/)
3.  [MIMIC-IV-ECG](https://physionet.org/content/mimic-iv-ecg/1.0/) - Diagnostic ECG data from MIMIC-IV.
4.   [PTB-XL: A large publicly available electrocardiography dataset](https://physionet.org/content/ptb-xl/1.0.3/)
5. [PhysioNet](https://physionet.org/) - Contains numerous other waveform databases (ECG, EEG, etc.) beyond MIMIC.

### Prescription Data
1.  [OpenPrescribing](https://openprescribing.net/) - Prescribing data from GPs in England.
2. [FDA Adverse Event Reporting System](https://www.fda.gov/drugs/surveillance/questions-and-answers-fdas-adverse-event-reporting-system-faers). Captures adverse drug reactions.

## Imaging Data

### Radiology (X-ray, CT, MRI)

1.  [TCIA (The Cancer Imaging Archive)](https://www.cancerimagingarchive.net/) - Excellent resource for cancer imaging.
2.  [Chest X-Ray Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) - Pneumonia detection.
3.  [RSNA Intracranial Hemorrhage Detection](https://www.kaggle.com/c/rsna-intracranial-hemorrhage-detection) - Head CT scans with hemorrhage labels.
4.  [MICCAI 2015 Challenge on Multimodal Brain Tumor Segmentation](https://academictorrents.com/details/c4f39a0a8e46e8d2174b8a8a81b9887150f44d50) - Brain tumor segmentation.
5.  [Non-Small Cell Lung Cancer CT Scan Dataset](https://academictorrents.com/details/95b58ebfc1952780cfe2102dd7290889feefad66)
6.  [PROSTATEx](https://academictorrents.com/details/5a447ff50062194bd58dd11c0fedead59e6d873c) - Prostate MRI.
7.  [MosMedData: Chest CT Scans with COVID-19 Related Findings](https://academictorrents.com/details/f2175c4676e041ea65568bb70c2bcd15c7325fd2)
8.  [LUng Nodule Analysis (LUNA16)](https://academictorrents.com/details/58b053204337ca75f7c2e699082baeb57aa08578) - Lung nodules.
9.  [NIH Chest X-ray Dataset of 14 Common Thorax Disease Categories](https://academictorrents.com/details/557481faacd824c83fbf57dcf7b6da9383b3235a)
10. [DeepLesion](https://academictorrents.com/details/de50f4d4aa3d028944647a56199c07f5fa6030ff) - CT images with lesions.
11. [Medical Segmentation Decathlon Datasets](https://academictorrents.com/details/274be65156ed14828fb7b30b82407a2417e1924a)
12. [dHCP 2nd data release -- sourcedata](https://academictorrents.com/details/515e2989eedc853a8e256424de112f6f48f10d80) - Developmental Human Connectome Project.
13. [dHCP 2nd data release -- fMRI pipeline](https://academictorrents.com/details/7197ed06604fcc7791d321afc229efe7c24dc472)
14. [PADCHEST_SJ](https://academictorrents.com/details/dec12db21d57e158f78621f06dcbe78248d14850) - Chest X-rays (Spanish labels).
15. [MURA (musculoskeletal radiographs)](https://stanfordmlgroup.github.io/competitions/mura/) - Stanford bone X-rays.
16. [National COVID-19 Chest Image Database (NCCID)](https://nhsx.github.io/covid-chest-imaging-database/) - UK COVID-19 imaging.
17. [International Neuroimaging Data-Sharing Initiative (INDI)](https://registry.opendata.aws/fcp-indi/)
18. [Open Access Series of Imaging Studies (OASIS)](https://www.oasis-brains.org/) - Brain MRI.
19. [BossDB Open Neuroimagery Datasets](https://registry.opendata.aws/bossdb/)
20. [NYU Langone & FAIR FastMRI Dataset](https://registry.opendata.aws/nyu-fastmri/) - Knee MRIs.
21. [The Human Connectome Project](https://registry.opendata.aws/hcp-openaccess/)
22. [RadGraph](https://physionet.org/content/radgraph/1.0.0/) - Radiology report entities/relations.
23. [RadNLI](https://physionet.org/content/radnli-report-inference/1.0.0/) - Radiology report inference.
24. [RadQA](https://physionet.org/content/radqa/1.0.0/) - Radiology report QA.
25. [UK Biobank Brain Imaging](https://www.ukbiobank.ac.uk/enable-your-research/about-our-data/neuroimaging-data) - *Requires application and approval.*
26. [ADNI (Alzheimer's Disease Neuroimaging Initiative)](http://adni.loni.usc.edu/) - *Requires application and approval.*
27. [The Cancer Genome Atlas (TCGA) Clinical Data Resource imaging data ](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=70226904). TCIA contains imaging data associated with subjects from TCGA.


### Ophthalmology

1.  [Labeled Optical Coherence Tomography](https://academictorrents.com/details/198145c88af9a1d61ba8070f5b05c3539896ff4e) - Retinal OCT.
2.  [e_ophtha](https://www.adcis.net/en/third-party/e-ophtha/) - A database of retinal images used for the detection of diabetic retinopathy.
3.  [DIARETDB0 and DIARETDB1](https://www.it.lut.fi/project/imageret/diaretdb1/) - Diabetic retinopathy databases and evaluation protocols.
4. [MESSIDOR and Base de Datos Oftalmologica de la Region de Murcia (BDOR-Murcia)](https://www.adcis.net/en/third-party/messidor/) - Datasets for computer-aided diagnosis of diabetic retinopathy.
5. [STARE (Structured Analysis of the Retina)](https://cecas.clemson.edu/~ahoover/stare/) - Retinal images with vessel segmentations and disease labels.
6.  [DRIVE: Digital Retinal Images for Vessel Extraction](https://www.isi.uu.nl/Research/Databases/DRIVE/) - Retinal images for vessel segmentation.
7.  [RFMiD](https://www.kaggle.com/datasets/andrewmvd/retinal-fundus-multi-disease-dataset) - Retinal Fundus Multi-disease Image Dataset.
8. [A-Fundus](https://data.mendeley.com/datasets/nk9r-fdrbp/1)- pediatric fundus images.

### Dermatology
1.  [ISIC Archive (International Skin Imaging Collaboration)](https://www.isic-archive.com/) - A large collection of dermoscopic images of skin lesions.
2.  [HAM10000 dataset](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T) - "Human Against Machine with 10000 training images" - dermoscopic images.
3.  [DermNet NZ](https://dermnetnz.org/image-library/) - While primarily a resource for information, DermNet NZ has a vast image library, though it is primarily for educational use and may have copyright restrictions.
4.  [PAD-UFES-20](https://data.mendeley.com/datasets/zr7vgbcyr2/1) - Skin lesion images with clinical data.

### Pathology

1.  [CAMELYON17 breast cancer](https://academictorrents.com/details/fedc1a6b331fb8d9e56001ebad8429621bbf2379) - Lymph node metastasis.
2.  [PatchCamelyon (PCam)](https://github.com/basveeling/pcam) - A benchmark dataset for machine learning, derived from Camelyon16.
3.   [Computational Precision Medicine](https://github.com/labsyspharm/cpm-pathology) - Giga-pixel pathology images from the University of Pittsburg.
4.  [The Cancer Genome Atlas (TCGA)](https://www.cancer.gov/tcga) - Includes histopathology images alongside genomic data. *Requires data use agreement and, for some data, IRB approval.*
5. [PANDA challenge](https://www.kaggle.com/c/prostate-cancer-grade-assessment/data) - Prostate cancer grade assessment.

### Microscopy

1.  [Cell Painting Gallery](https://registry.opendata.aws/cellpainting-gallery/) - Drug discovery.
2.  [Allen Cell Imaging Collections](https://registry.opendata.aws/allen-cell-imaging-collections/) - 3D cell imaging.
3. [BBBC (Broad Bioimage Benchmark Collection)](https://bbbc.broadinstitute.org/) - A collection of freely available, high-quality, biological image datasets.

### Dental

1.  [A multimodal dental dataset facilitating machine learning research and clinic services](https://physionet.org/content/multimodal-dental-dataset/1.0.0/)

### Other Imaging Modalities

1.  [MIMIC-IV-ECHO](https://physionet.org/content/mimic-iv-echo/0.1/) - Echocardiogram data from MIMIC-IV.
2. [EchoNet-Dynamic](https://echonet.github.io/dynamic/) - Echocardiogram videos with ejection fraction measurements

## Omics Data

### Genomics

1.  [TCGA (The Cancer Genome Atlas)](https://www.cancer.gov/ccg/research/genome-sequencing/tcga) - *Requires data use agreement.*
2.  [1000 Genomes Project](https://www.internationalgenome.org/data/)
3.  [Genome Aggregation Database](https://registry.opendata.aws/broad-gnomad/)
4.  [Genome in a Bottle on AWS](https://registry.opendata.aws/giab/) - Reference genomes.
5.  [GDC (Genomic Data Commons)](https://portal.gdc.cancer.gov/) - *Requires data use agreement.*
6. [UK Biobank](https://www.ukbiobank.ac.uk/) *Requires extensive application process*.

### Transcriptomics

1.  [GTEx (Genotype-Tissue Expression)](https://gtexportal.org/home/)
2.  [Gene Expression Omnibus (GEO)](https://www.ncbi.nlm.nih.gov/geo/)
3.  [ArrayExpress](https://www.ebi.ac.uk/arrayexpress/)
4.  [Expression Atlas](https://www.ebi.ac.uk/gxa/home) - A curated resource that provides information on gene expression across species and biological conditions.

### Proteomics

1. [Clinical Proteomic Tumor Analysis Consortium 3 (CPTAC-3)](https://registry.opendata.aws/cptac-3/)
2.  [Protein Data Bank (PDB)](https://www.rcsb.org/) - Protein structures.
3.  [Human Protein Atlas](https://www.proteinatlas.org/)
4.  [UniProt](https://www.uniprot.org/) - Protein sequences and annotations.
5.  MassIVE (https://massive.ucsd.edu/) and ProteomeXchange (http://www.proteomexchange.org/) - Repositories for mass spectrometry proteomics data.

### Metabolomics

1.  [Human Metabolome Database](https://hmdb.ca/)
2.  [Metabolomics Workbench](https://www.metabolomicsworkbench.org/) - A public repository for metabolomics data and metadata.

### Multi-omics
1. [cBioPortal](https://www.cbioportal.org/) - Cancer genomics.
2.  [LinkedOmics](http://www.linkedomics.org/)- A web portal that integrated TCGA data with CPTAC proteomic data.
3. [PRECOG](https://precog.stanford.edu/) - PREdiction of Clinical Outcomes from Genomic profiles

### Pharmacogenomics

1.  [Cancer Cell Line Encyclopedia (CCLE)](https://registry.opendata.aws/ccle/)
2.  [CoMMpass from the Multiple Myeloma Research Foundation](https://registry.opendata.aws/mmrf-commpass/)
3.  [NIH NCBI Sequence Read Archive (SRA) on AWS](https://registry.opendata.aws/ncbi-sra/)
4.  [Basic Local Alignment Sequences Tool (BLAST) Databases](https://registry.opendata.aws/ncbi-blast-databases/)
5.  [Encyclopedia of DNA Elements (ENCODE)](https://registry.opendata.aws/encode-project/)
6.  [Tox21](https://tripod.nih.gov/tox21/challenge/)
7.  [CTRP (Cancer Therapeutics Response Portal)](https://portals.broadinstitute.org/ctrp.v2.1/)
8. [PharmGKB](https://www.pharmgkb.org/)
9. [GDSC (Genomics of Drug Sensitivity in Cancer)](https://www.cancerrxgene.org/) - A large-scale database of drug sensitivity in cancer cell lines.

## Biomedical Knowledge Graphs and Ontologies

### General Medical Terminologies

1.  [UMLS (Unified Medical Language System)](https://www.nlm.nih.gov/research/umls/index.html)
2.  [SNOMED CT](https://www.snomed.org/) - *Requires a license, free in some countries.*
3.  [LOINC (Logical Observation Identifiers Names and Codes)](https://loinc.org/)
4.  [MeSH (Medical Subject Headings)](https://www.ncbi.nlm.nih.gov/mesh)
5.  [ICD-10 (International Classification of Diseases, 10th Revision)](https://www.cdc.gov/nchs/icd/icd10cm.htm)
6.  [ICD-9 (International Classification of Diseases, 9th Revision)](https://www.cdc.gov/nchs/icd/icd9cm.htm)
7.  [CPT (Current Procedural Terminology)](https://www.ama-assn.org/amaone/cpt-current-procedural-terminology) - *Requires a license.*
8.  [Medical Dictionary for Regulatory Activities Terminology](https://www.meddra.org/) *Requires a license.*
9.  [International Classification of Diseases for Oncology](https://www.who.int/standards/classifications/other-classifications/international-classification-of-diseases-for-oncology)

### Drug and Chemical Information

1.  [RxNorm](https://www.nlm.nih.gov/research/umls/rxnorm/)
2.  [DrugBank](https://go.drugbank.com/)
3.  [RxMix](https://mor.nlm.nih.gov/RxMix/)
4.  [RxTerms](https://lhncbc.nlm.nih.gov/MOR/RxTerms/)
5.  [Dailymed](https://dailymed.nlm.nih.gov/dailymed/app-support-mapping-files.cfm)
6. [PubChem](https://pubchem.ncbi.nlm.nih.gov/)
7. [ChEMBL](https://www.ebi.ac.uk/chembl/)
8.  [SIDER](http://sideeffects.embl.de/) - Drug side effects.
9.  [STITCH](http://stitch.embl.de/) - Chemical-protein interactions.
10. [ZINC](https://zinc.docking.org/) - Compounds for virtual screening.

### Disease and Gene Information

1.  [Orphanet Rare Disease Ontology](https://www.orpha.net/consor/cgi-bin/index.php)
2.  [GWAS Catalog](https://www.ebi.ac.uk/gwas/)
3.  [Gene Ontology](http://geneontology.org/)
4.  [Disease Ontology](http://disease-ontology.org/)
5.  [Genetic and Rare Diseases](https://rarediseases.info.nih.gov/)
6.  [Online Mendelian Inheritance in Man](https://www.omim.org/)
7.  [DisGeNET](https://www.disgenet.org/)
8. [ClinVar](https://www.ncbi.nlm.nih.gov/clinvar/) - A public archive of reports of the relationships among human variations and phenotypes.
9. [HGNC (HUGO Gene Nomenclature Committee)](https://www.genenames.org/) - Provides approved human gene nomenclature.

### Pathway and Interaction Databases

1. [Reactome](https://reactome.org/)
2. [EXPERIMENTAL FACTOR ONTOLOGY](https://www.ebi.ac.uk/efo/).
3. [UBERON anatomy](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2012-13-1-r5).
4. [Kyoto Encyclopedia of Genes and Genomes](https://www.genome.jp/kegg/)
5.  [Open-targets](https://ftp.ebi.ac.uk/pub/databases/opentargets/platform/latest/output/etl/parquet/)
6. [STRING](https://string-db.org/) - A database of known and predicted protein-protein interactions.
7. [BioGRID](https://thebiogrid.org/) - A database of protein and genetic interactions.
8.  [IntAct](https://www.ebi.ac.uk/intact/) - A molecular interaction database.

## Public Health Data

### Global Health

1.  [Global Health Observatory (GHO)](https://www.who.int/data/gho/)
2.  [World Bank Health Data](https://data.worldbank.org/topic/health)
3.  [Global Burden of Disease (GBD)](http://www.healthdata.org/gbd)
4.  [UNICEF Data](https://data.unicef.org/)
5.  [OECD Health Statistics](https://www.oecd.org/els/health-systems/health-data.htm)
6.  [Humanitarian Data Exchange](https://data.humdata.org/)
7.   [Institute for Health Metrics and Evaluation](http://www.healthdata.org/) - provides access to many more datasets related to global health.

### US-Specific Public Health

1.  [CDC WONDER](https://wonder.cdc.gov/)
2.  [Medicare.gov Data](https://data.medicare.gov/)
3.  [HealthData.gov](https://healthdata.gov/)
4.  [Medicare Provider Utilization and Payment Data](https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data)
5.  [National Health and Nutrition Examination Survey (NHANES)](https://www.cdc.gov/nchs/nhanes/index.htm)
6. [SEER (Surveillance, Epidemiology, and End Results Program)](https://seer.cancer.gov/) - Cancer statistics. *Requires data use agreement.*
7. [Behavioral Risk Factor Surveillance System (BRFSS)](https://www.cdc.gov/brfss/index.html) - Health-related telephone surveys.
8. [Youth Risk Behavior Surveillance System (YRBSS)](https://www.cdc.gov/healthyyouth/data/yrbs/index.htm) - Monitors health-risk behaviors among youth.

### Health Systems and Policy
1.  [All of Us Research Program](https://www.researchallofus.org/)
2.  [Canadian Open Neuroscience Platform (CONP)](https://portal.conp.ca/)
3. [Pharmaceuticals and Medical Devices Agency Japan](https://www.pmda.go.jp/english/pnavi_e-05.html).
4. [European Medicines Agency](https://www.ema.europa.eu/en/homepage).
5. [Kaiser Permanente Research Bank](https://researchbank.kaiserpermanente.org/) - Data from Kaiser Permanente, a large integrated healthcare delivery system (requires application and proposal).
6. [Truven Health MarketScan Databases](https://www.ibm.com/products/marketscan-research-databases) - Commercial claims and EMR data. (Requires purchase.)
7.  [Optum Clinformatics Data Mart](https://www.optum.com/business/life-sciences/real-world-data.html) - Commercial claims and EMR data. (Requires purchase, academic subscriptions available).
8. [National Inpatient Sample (NIS)](https://www.hcup-us.ahrq.gov/nisoverview.jsp) - Largest all-payer inpatient care database in the US. (Available for purchase.)
9. [National Ambulatory Medical Care Survey (NAMCS) and National Hospital Ambulatory Medical Care Survey (NHAMCS)](https://www.cdc.gov/nchs/ahcd/index.htm)- Provides data on ambulatory care visits.

## Biomedical Literature

### Article Databases and Collections

1.  [PubMed Central Open Access Subset](https://www.ncbi.nlm.nih.gov/pmc/tools/openftlist/)
2.  [CORD-19](https://allenai.org/data/cord-19) - COVID-19 papers.
3.  [LitCovid](https://www.ncbi.nlm.nih.gov/research/coronavirus/) - COVID-19 literature.
4.  [PubMed](https://pubmed.ncbi.nlm.nih.gov/)
5.  [Europe PMC](https://europepmc.org/)
6.  [Microsoft Academic Graph](https://www.microsoft.com/en-us/research/project/microsoft-academic-graph/)
7.   [Semantic Scholar Open Research Corpus](https://allenai.org/data/s2orc)

### Literature-Based Datasets
1. [BioASQ](http://bioasq.org/) - Biomedical semantic indexing and question answering challenges.
2.  [ChemProt](https://biocreative.bioinformatics.udel.edu/tasks/biocreative-vi/track-5/) - Chemical-protein interactions extracted from literature.
3.  [DDI (Drug-Drug Interaction) Extraction](https://labh-curran.ucd.ie/datasets/index.php) - Drug-drug interaction extraction from biomedical texts.

## Wearable and Sensor Data

1.  [PhysioNet](https://physionet.org/) - (See also Waveform Data) Contains numerous datasets from wearable sensors.
2.  [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php) - Contains several smaller datasets related to wearable sensor data, activity recognition, etc.
3. [The BIDMC PPG and respiration dataset](https://physionet.org/content/bidmc/1.0.0/) - Photoplethysmogram (PPG), respiration, and other physiological signals.
4. [VitalDB](https://vitaldb.net/) - Vital signs data collected during surgeries
5. [mHealth Dataset](https://archive.ics.uci.edu/dataset/319/mhealth+dataset) - Body motion and vital signs data.
6.  [Opportunity Dataset](https://archive.ics.uci.edu/ml/datasets/opportunity+activity+recognition) - Daily living activity recognition data.

## Social Determinants of Health (SDOH)

1.   [American Community Survey (ACS)](https://www.census.gov/programs-surveys/acs) - Provides detailed demographic, socioeconomic, and housing data at various geographic levels.
2.   [Area Health Resources Files (AHRF)](https://data.hrsa.gov/topics/health-workforce/ahrf) - County-level data on healthcare resources, demographics, and social determinants.
3.    [County Health Rankings & Roadmaps](https://www.countyhealthrankings.org/) - Provides rankings and data on various health factors and outcomes at the county level.
4.    [USDA Food Environment Atlas](https://www.ers.usda.gov/data-products/food-environment-atlas/) - Data on food access, food prices, and local food systems.
5.   [Robert Wood Johnson Foundation (RWJF) Data Hub](https://www.rwjf.org/en/data-hub.html) - Curated datasets related to health equity and social determinants.

## Synthetic Data
1. [Synpuf](https://www.cms.gov/research-statistics-data-and-systems/downloadable-public-use-files/synpufs) - Medicare synthetic data.
2.  [Synthea](https://synthetichealth.github.io/synthea/) - A synthetic patient generator that models the medical history of US patients.
3. [MedGAN](https://github.com/usc-Melady/MedGAN) - Generating Multi-label Discrete Patient Records using Generative Adversarial Networks.
4. [CorGAN](https://arxiv.org/abs/1903.02629) - Correlation-Capturing Convolutional Generative Adversarial Networks for Generating Synthetic Healthcare Time-Series Data.

## Miscellaneous

1.  [Human Mortality Database](https://www.mortality.org/)
2.  [OpenNeuro](https://openneuro.org/) - Neuroimaging data.
3. IBL Neuropixels Reproducible Ephys Data on AWS](https://registry.opendata.aws/ibl-reproducible-ephys/).
4.  [Human Cell Atlas](https://www.humancellatlas.org/)
5. [Refgenie reference genome assets](https://registry.opendata.aws/refgenie/).
6. [Open Bioinformatics Reference Data for Galaxy](https://registry.opendata.aws/open-bio-ref-data/).
7. [OpenCell on AWS](https://registry.opendata.aws/czb-opencell/).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released into the public domain. See the [license file](https://github.com/yourusername/awesome-healthcare-datasets/blob/master/LICENSE) for more details.
