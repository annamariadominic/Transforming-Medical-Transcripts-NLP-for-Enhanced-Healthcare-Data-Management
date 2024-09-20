# Transforming-Medical-Transcripts-NLP-for-Enhanced-Healthcare-Data-Management

This project converts unstructured EHR data into structured formats using diverse classification models, with T5 playing a key role in transforming transcriptions. The approach improves data categorization, enhances healthcare data management, and facilitates efficient storage, feature identification, and predictive modeling.

### Key Features
- **Data Transformation:** Utilizes regex and GPT-based methods to extract structured information from medical transcripts.
- **Classification Models:** Implements Multinomial Naive Bayes, Logistic Regression, Word2Vec, and LightGBM for accurate classification of medical data.
- **T5 Model Integration:** Leverages T5’s sequence-to-sequence capabilities to convert unstructured transcriptions into actionable, structured data.
- **Advanced Evaluation:** Employs metrics like ROC AUC for classification tasks and ROUGE-L for sequence generation to ensure robust performance.
- **Dataset:** Based on a Kaggle dataset with over 5,000 medical transcripts spanning various specialties and cases.

### Methodology
1. **Data Extraction:** Using regular expressions and GPT-3.5, key entities such as age, disease, and symptoms are extracted from medical transcriptions.
2. **Classification Models:** Multiple machine learning models were implemented to categorize transcriptions by gender, medical specialty, and treatment type. Feature engineering was carried out using TF-IDF to optimize classification accuracy.
3. **T5 for Sequence Generation:** The T5 model was integrated for sequence generation tasks, converting unstructured data into structured formats.
4. **Evaluation Metrics:** Classification models were evaluated using ROC AUC, and the T5 model was evaluated using ROUGE-L to ensure robustness.

### Results
- **Improved Accuracy:** Achieved over 90% accuracy in gender classification and around 95% in medical specialty and treatment type prediction using Logistic Regression.
- **T5 Performance:** Optimal performance was achieved with a learning rate of 1e-4, batch size of 4, and 10 epochs, resulting in precision of 0.261, recall of 0.346, and F1 score of 0.298 for sequence generation.

### Conclusion
This project presents a robust approach to transforming unstructured EHR data into structured formats, leveraging the strengths of diverse machine learning models and the T5 model for data transformation. The methodology demonstrates improved data management, categorization, and predictive modeling in healthcare settings.
