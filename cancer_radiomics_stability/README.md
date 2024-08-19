# Cancer Radiomics Stability project

## Objective
The objective of this project is to explore the variability in radiomic features extracted from medical images and assess how this variability impacts the performance of predictive models. The focus is on stabilizing these features to improve model reliability, particularly in the context of cancer prognosis.

## Step
1. Data Collection and Preparation:
2. Feature Variability Analysis
3. Model Development
4. Performance Evaluation:
5. Validation and Testing:

## Result
1. The variability in radiomic features across different annotations significantly impacts model performance.
2. Stabilizing features using the median across annotations improves the robustness of the predictive models.
3. Neural networks, with a focus on recall, perform better in identifying high-risk patients when compared to random forests, which may be less sensitive to the variability in the data.
4. The final model achieves a balanced trade-off between precision and recall, ensuring that the most at-risk patients are identified for further medical intervention.
## Documentation
1. [CancerRadiomicsKaggle_Stability_v1_042120.csv](https://github.com/micsupasun/classification/blob/main/cancer_radiomics_stability/CancerRadiomicsKaggle_Stability_v1_042120.csv): This file contains the first version of the radiomic features dataset, including raw feature values and possibly some initial annotations or preprocessing steps.
2. [CancerRadiomicsKaggle_v2_050620.csv](https://github.com/micsupasun/classification/blob/main/cancer_radiomics_stability/CancerRadiomicsKaggle_v2_050620.csv): This file appears to be an updated version of the dataset, possibly including more refined annotations, additional features, or a more extensive preprocessing pipeline.
3. [exercise_2_code_answer.ipynb](https://github.com/micsupasun/classification/blob/main/cancer_radiomics_stability/exercise_2_code_answer.ipynb): A Jupyter notebook that contains the code for the analysis and model development. It includes data preprocessing, feature variability analysis, model training, and performance evaluation.
4. [exercise_two_answer.docx](https://github.com/micsupasun/classification/blob/main/cancer_radiomics_stability/exercise_two_answer.docx): A document that describes the rationale behind the choice of models, evaluation metrics, and the steps taken to address the feature variability issue in radiometric data.
