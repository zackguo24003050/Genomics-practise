# Genomic practise: Scenario A

Jane Doe, a 54 year old female, presented with a lump in her left breast. Mammogram identified a region of abnormal breast tissue. Histopathological analysis of a biopsy identified cells with large nuclei to cytoplasmic ratio. Further immunohistochemical analysis showed that the cells with large nuclei are estrogen receptor negative, progesterone receptor negative, and HER2 positive. Sequencing of the remaining sample revealed:

BRCA2 E1158Q  
13q loss  
ERBB2 amplification  
chr17:g.7676106del  
chr3:g.179218294G>A  

Note: Coordinates are based on GRCh38.

## What is the diagnosis? Be as specific as possible and explain the supporting evidence.

Pheno:  
A lump is seen at breast, indicating the possibility of breast cancer，supported by abnormal breast tissue in Mammogram. Large nuclei to cytoplasmic ratio is a feature of cancer cells.  
Genetic:  
BRCA2, a tumor suppressor gene, has a mutation. The 1158th E(Glutamic acid) changes to Q(glutamine).  
Loss of material in chromosome 13 long arm.  
ERBB2(HER2) is amplified, indicating up-regulated HER2 pathway, leading to tumor growth.  
A deletion of base in 7676106th position in chromosome 17.  
A change from G to A in 179218294th position in chromosome 3.  
In conclusion, I think this is HER2-positive invasive ductal carcinoma.

## What is the expected 5-year overall survival of this patient based on the totality of evidence? Cite your reference.

For regional cancer, the 5-year relative survival rate is 90.4% for HR-positive and HER2-positive and 84.2% for HR-negative and HER2-positive cancer.  
If cancer has spread to another part of the body, the 5-year relative survival rates are 45.8% for HR-positive and HER2-positive cancer and 39.7% for HR-negative and HER2-positive cancer.  (1)

## Which targeted therapy may be effective for this patient? Cite your reference.

Kinase inhibitors such as: lapatinib, neratinib, and tucatinib.  
Monoclonal antibody such as: Trastuzumab, Margetuximab, and Pertuzumab.  (2)


## What is the original codon at chr17:7676106? What is the amino acid?

This codon is located in the TP53 gene. GGC in reverse strand in UCSC genome browser, so actually CGG. Proline.(https://genome.ucsc.edu/)

## What amino acid change will result from the chr17:g.7676106del mutation? What will be the functional consequences?

Frameshift results in a stop codon 6 amino acid downstream. So TP53 protein is not transcribed. Loss of function.

## What is the original codon at chr3:179218294? What is the amino acid?

This codon is in PIK3CA. ACT. Glu.

## What amino acid change will result from the chr3:g.179218294G>A mutation? What will be the functional consequences?

Glu to Lys. A acidic amino acid to a basic amino acid. The amino acid is in the catalytic subunit of PIK3CA, increasing its activity, leading to AKT activation and oncogenic transformation.

## Explain how many functional copies of BRCA2 remain in the sample.

0. Loss of material in 13q has caused a loss of one copy of BRCA2. The remaining one gains a mutation of E1158Q. As a result. There is no functional BRCA2 remaining.

#Reference
(1)National Cancer Institute. “Female Breast Cancer Subtypes - Cancer Stat Facts.” SEER, 2024, seer.cancer.gov/statfacts/html/breast-subtypes.html.
(2)Tolu Ajiboye. “MNT Investigates: Anti-HER2 Drugs and the Fight against Metastatic Breast Cancer.” Medicalnewstoday.com, Medical News Today, 19 May 2021, www.medicalnewstoday.com/articles/anti-her2-drugs-and-the-fight-against-mbc#future-of-treatment. Accessed 31 Mar. 2025.
