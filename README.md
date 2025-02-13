Replication Package for the paper entitled"-------"

Datasets: To answer the research questions, we considered two different datasets. The first is the same one used in: "S. Cresci, R. Di Pietro, M. Petrocchi, A. Spognardi, and M. Tesconi, “The paradigm-shift of social spambots: Evidence, theories, and tools for the arms race,” in Proceedings of the 26th international conference on World wide web companion, 2017, pp. 963–972", which comprises actual human authors with numerous tweets. The LLMs datasets are built using 10 different models using three prompts and are presented below, we took the human samples from the human dataset (Human-Extraction.csv).

1. Prompt-01-Extraction.csv; (Setup-01)
2. Prompt-02-Extraction.csv; (Setup-02)
3. Prompt-03-Extraction.csv (Setup-03)

We extract features and determine the mean and STD using the following Programs:

1. LLMFeaturesExtraction.ipynb
2. Mean&STD.ipynb


Features Emulation: To address RQ1, We determine which stylometric features can be effectively mimicked by different LLMs using the following file:

1. LLMFeaturesEmulation.ipynb

Survey: To address RQ2, the following file represents the survey results:

1.

Detection Models: To address RQ3, to detect the LLMs and human authors, we chose five supervised machine learning (ML) models, namely Linear Support Vector Machine, Support Vector Machines with RBF kernel, Logistic Regression, Decision Tree, and Random Forest, organized all in .ipynb files:

1. DecisionTree.ipynb;
2. LogisticRegression.ipynb;
3. RandomForest.ipynb;
4. SVMLinear.ipynb;
5. SVM_RBF.ipynb
