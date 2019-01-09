# BMI 704: Data Science for Medical Decision Making<br>
## Harvard Medical School<br>
### Spring 2019<br>
### Course Directors: Chirag J. Patel, Arjun K. Manrai

## Course Description
Have you ever Googled a health-related question and been dumbfounded by the hits? Gotten a lab test result and wondered if it applies to a person like you? Wondered what an "odds ratio" for a genetic variant you inherited is? Explanations of why we are who we are, and what diseases we might get, and why some of us are at risk, are often unsatisfactory. It’s time to become an active consumer: in this course, we will develop skills in querying large health data streams to make informed decisions through the lens of data science. This course will survey the current data and methodological approaches to conduct integrative high-throughput investigations merging genomic, exposomic, and phenomic datasets to discover new associations with disease and health. Students will be introduced to statistical decision theory and how modern data science and machine learning approaches can help improve rational medical decision making. Students will be encouraged to find publicly available data (e.g. CDC, NIH dbGaP data) and formulate an original research project for submission to a journal or as a proceedings article.Learning 

Goals:
1. Develop basic skills in biomedical data science, including R/RStudio, Python and cloud-based infrastructure.
2. Understand how decision theory and machine learning can enhance clinical care.
3. Develop your own prediction algorithms that integrate exposomic, genomic, and phenomic data.
4. Execute data-driven methods on current day computing clusters.
5. Interpret statistical estimates and biomedical findings in the published literature (and the lay press).

# Course Calendar
| Date (Week)  | Topics | Readings (before lecture) | Assignments (due 11:00pm) |
| :---: | ----------------------- | ------------- | ------------- |
|<b>1/31<br>(1)</b>|<b>Data-driven investigations into fundamental questions in biomedicine</b><ol><li>Introduction to the course</li><li>Overview of P = G + E (Phenotype = Genotype + Environment)</li><li>Conducting reproducible research</li><li>Data science in R/RStudio and cloud computing</li><li>Introduction to traditional observational and agnostic ‘omic (e.g. GWAS) study designs</li></ol>|<b>Recommended:</b><br>(Wickham and Grolemund 2016; <br>Paul R Burton et al. 2007; <br>Pearson and Manolio 2008)|<b>Assignment 1 out</b> (GWAS and polygenic risk prediction)|
|<b>2/7<br>(2)</b>|<b>Genome-wide association studies (GWAS): an example of data-driven biomedicine for G in P</b><ol><li>Practical data science with the tidyverse [guest lecture: Chirag Lakhani]</li><li>High-throughput genomics: dissecting G in P with GWAS</li><li>GWAS fundamentals: p-values, Bonferroni, odds ratios, and qq-plots</li><li>LD, population stratification, and confounding</li><li>Polygenic risk prediction</li></ol>|<b>Required:</b><br>(Wickham and Grolemund 2016; <br> Paul R Burton et al. 2007; <br>Pearson and Manolio 2008; <br>Price et al. 2006; <br>Khera et al. 2018; <br>Vittinghoff et al. 2005: Chapters 1-5)<br><br><b>Recommended:</b><br>(Visscher et al. 2017, 2012; <br>Risch and Merikangas 1996)||
|<b>2/14<br>(3)</b>|<b>Dissecting E in P & Machine Learning Part 1</b><ol><li>History of modifiable E associations (SES, vitamins, physical activity, air pollution)</li><li>Comparison with G associations</li><li>Intro to EWAS</li><li>Intro to machine learning and fundamental concepts</li><li>The bias-variance tradeoff</li><li>Regularization (e.g. L1, L2)</li></ol>|<b>Required:</b><br>(Marmot et al. 1978; <br>Dockery et al. 1993; <br>Ioannidis et al. 2009; <br>Freedman et al. 2012; <br>Patel et al. 2012)<br><br><b>Recommended:</b><br>(Lee et al. 2018; <br>Kong et al. 2018; <br>Manson et al. 2018; <br>Di et al. 2017; <br>Patel and Manrai 2015)|<b>Assignment 2 out</b> (EWAS)|
|<b>2/21<br>(4)</b>|<b>Why Most Published Research Findings are False</b><ol><li>Introduction to “Why Most Research Findings are False”</li><li>Types of study bias</li><li>Correcting for multiple tests (FWER, FDR)</li><li>Meta-research: research on research</li><li>Randomization: how to interpret a clinical trial</li></ol>|<b>Required:</b><br>(Ioannidis 2005; <br>Benjamini and Hochberg 1995; <br>Patel, Burford, and Ioannidis 2015; <br>Manson et al. 2019)<br><br><b>Recommended:</b><br>(Manson et al. 2018; <br>Estruch et al. 2018; <br>Video: https://goo.gl/REHTc2)|<b>Guided project out</b>(Field-wide meta-analysis + PheWAS in NHANES/UKB)|
|<b>2/28<br>(5)</b>|<b>Decision Making in Medicine</b><ol><li>Intro to decision science in medicine</li><li>Categorical and probabilistic reasoning in medicine</li><li>Cognitive biases in medical decision making (e.g. numeracy)</li><li>Supporting physicians at the point of care</li><li>Guest Lecture: Vinay Prasad (http://www.vinayakkprasad.com/)</li></ol>|<b>Required:</b><br>(Szolovits and Pauker 1978; <br>Tversky and Kahneman 1974; <br>Manrai et al. 2016; <br>Prasad et al. 2013)<br><br><b>Recommended:</b><br>(Bates et al. 1998; <br>Mandl and Kohane 2012)|
|<b>3/7<br>(6)</b>|<b>Clinical Risk Scores and Machine Learning Part 2</b><ol><li>Introduction to time-series analysis: the Kaplan-Meier estimator and Cox regression</li><li>Disease Risk Scores (e.g. Charlson comorbidity index)</li><li>Heritability and AUC</li><li>Practical machine learning</li><li>Evaluating model fit</li></ol>|<b>Required:</b><br>(James et al. 2013: Chapters 2, 3, 4, 5.1, 6; <br>Horvath 2013; <br>Lloydjones et al. 2004; <br>Meigs et al. 2008; <br>Charlson et al. 1987)<br><br><b>Recommended:</b>(Vittinghoff et al. 2005: Chapter 6; <br>Lakhani 2019)|<b>Lab out</b> (machine learning)|
|<b>3/14<br>(7)</b>|<b>Bringing it All Together</b><ol><li>Short student presentations and real-time meta-analysis</li><li>Press-reported results: fake news?</li><li>Emerging topics in observational datasets: Guest Lecturer: Mauricio Santillana, PhD</li>|<b>Required:</b><br>(Baicker et al. 2013; <br>Collins and Varmus 2015; <br>Schoenfeld and Ioannidis 2012)<br><br><b>Recommended:</b>Video: https://goo.gl/rnruXK||
  
  ## Datasets Used in this Course:
Descriptions below are adapted from the URLs.

### Genetic Data
| Dataset  | Description | URL |
| ------------- | ------------- | ------------- |
| Wellcome Trust Case Control Consortium (WTCCC) | Early example of the feasibility of genome-wide association studies (GWAS) | https://www.wtccc.org.uk/ |
| 1000 Genomes Project Phase 3 Data | A catalogue of individual-level genomic variation from 2,504 individuals across 26 worldwide populations | http://www.internationalgenome.org/ |
| Genome Aggregation Database (gnomAD) | Database that aggregates allele frequencies from exome and genome sequencing data for >140,000 indiivduals across 8 populations | http://gnomad.broadinstitute.org/ |
| NIH dbGaP | Archive of data and results from many genotype-phenotype studies | https://www.ncbi.nlm.nih.gov/gap |
| NHGRI-EBI GWAS Catalog | Curated collection of published GWAS results | https://www.ebi.ac.uk/gwas/ |
| Broad Institute Polygenic Risk Scores | Variants and weights for polygenic risk scores in Khera et al. 2018 | http://www.broadcvdi.org/informational/data |
| ClinVar | Database that aggregates assertions about pathogenicity of genetic variants across testing laboratories | https://www.ncbi.nlm.nih.gov/clinvar/ |
| UK Biobank  | U.K. cohort studying the health and well-being of 500,000 volunteer participants | https://www.ukbiobank.ac.uk/ |

### Exposure Data
| Dataset  | Description | URL |
| ------------- | ------------- | ------------- |
| CDC National Health and Nutrition Examination Survey (NHANES) | Series of ongoing studies combining interviews and physical exams designed to assess the health and nutritional status of adults and children in the United States | https://www.cdc.gov/nchs/nhanes/index.htm |
| Demographic and Health Surveys | Nationally-representative household surveys that provide data for a wide range of health and nutrition indicators | https://dhsprogram.com/what-we-do/survey-Types/dHs.cfm |
| American Community Survey (ACS) | Survey compiled by the U.S. Census Bureau with demographic data | https://www.census.gov/programs-surveys/acs/ |

### Phenotype Data
| Dataset  | Description | URL |
| ------------- | ------------- | ------------- |
| CDC National Health and Nutrition Examination Survey (NHANES) | Series of ongoing studies combining interviews and physical exams designed to assess the health and nutritional status of adults and children in the United States | https://www.cdc.gov/nchs/nhanes/index.htm |
| 500 Cities Project | City and census tract-level small area estimates for chronic disease risk factors, health outcomes, and clinical preventive service use for the largest 500 cities in the United States. | https://www.cdc.gov/500cities/index.htm |
| UK Biobank  | U.K. cohort studying the health and well-being of 500,000 volunteer participants | https://www.ukbiobank.ac.uk/ |
| Demographic and Health Surveys | Nationally-representative household surveys that provide data for a wide range of health and nutrition indicators | https://dhsprogram.com/what-we-do/survey-Types/dHs.cfm |
