# Microbiota adaptation review

Martin-Bideguren G, Razgour O, Alberdi A. 2023. **Quantitative synthesis of microbe-driven acclimation and adaptation in wild vertebrates**. Submitted.

## 1. Data search
(wild*) AND (animal*) AND (adapt*) AND (“gut microbiota” OR “gut microbiome” OR “intestinal microbiota” OR “intestinal microbiome” OR “GUT microbiota” OR “GUT microbiome”)

## 2. Data preprocessing
The reference code can be found in the Codes folder in the *1-Article_preprocessing.Rmd* file. Also a pdf version of the markdown file can be found in the same folder.

## 3. Study screening
The programmatic search and the initial filtering yielded 1974 studies, which were manually screened to analyse whether they met the following inclusion criteria: the study i) analyses the gut microbiota, ii) revolves around or touches upon environmental adaptations, iii) is focused on wild vertebrates and iv) is based on empirical data. This second filtering resulted in 109 studies, which were scrutinised to assign performance scores.
Scores asigned to each one of the 109 studies can be found in the Data folder in the *Adaptation.Review.supplement.dataset.b* file, note that all the values range from 0 to 1.

## 4. Study scoring
Each of the ten analysed criteria was given a different weight to obtain the overall performance scores through weighted average calculation. To minimise subjectivity, we requested 8 independent experts to assign relevance values to each of the ten criteria. The average values of the the criteria can be found in the folder Data in the *Scores_weight.csv* file.
   
## 5. Study analysis
The reference code can be found in the Codes folder in the *2-Data_analysis.Rmd* file. Also a pdf version of the markdown file can be found in the same folder.
