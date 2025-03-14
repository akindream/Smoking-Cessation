Here’s your GitHub README for the **Tobacco Usage Cessation Prediction Using Artificial Neural Networks** project:  

---

# **Tobacco Usage Cessation Prediction Using Artificial Neural Networks**  

## **Overview**  
Tobacco cessation is a significant public health challenge worldwide. Understanding and predicting tobacco usage cessation outcomes can help develop more effective and personalized intervention programs. This project leverages **Artificial Neural Networks (ANNs)** to predict tobacco cessation outcomes using real-world data from the **National Quitline Data Warehouse (NQDW)**.  

## **Objective**  
The goal of this study is to analyze a dataset of tobacco users and develop **ANN models** to classify and predict tobacco cessation outcomes. These models incorporate **demographic, behavioral, and psychological factors** to enhance predictive accuracy.  

## **Dataset**  
- **Source:** National Quitline Data Warehouse (NQDW)  
- **Participants:** 5,230 tobacco users registered between **2010 and 2020**  
- **Target Variable:** 30-day point-prevalence tobacco abstinence (success or failure in quitting tobacco)  
- **Data Split:**  
  - **Training Data:** 2010 – 2017  
  - **Validation/Test Data:** 2018 – 2020  

## **Methodology**  
Three different **Artificial Neural Network models** were implemented using a **supervised learning approach**:  
1. **Convolutional Neural Network (CNN)**  
2. **Long Short-Term Memory (LSTM)**  
3. **Gated Recurrent Unit (GRU)**  

Each model was trained using historical data and validated using the test set to evaluate its predictive power. **Classification metrics** were used to assess the models' performance.  

## **Results**  
The models achieved the following accuracy scores in predicting tobacco cessation outcomes:  

✅ **GRU:** **84.05%** (Best Performance)  
✅ **CNN:** **82.64%**  
✅ **LSTM:** **80.43%**  

The **GRU model** demonstrated the highest accuracy, making it the most effective predictor of tobacco cessation among the models tested.  

## **Key Insights**  
🔹 **Predictive Power**: The ANN models accurately predict tobacco cessation outcomes for at least **4 out of 5 individuals**.  
🔹 **Model Performance**: GRU outperforms CNN and LSTM in predicting tobacco cessation, likely due to its ability to **capture long-term dependencies in sequential data**.  
🔹 **Potential Impact**: These models provide **valuable insights for public health policies** and can help design more **effective smoking cessation programs**.  

## **Conclusion**  
This project highlights the power of **Artificial Neural Networks** in predicting tobacco cessation outcomes. The insights gained from these models can help healthcare providers, policymakers, and support programs refine their **intervention strategies** and tailor assistance to individuals more effectively.  

## **Future Work**  
🔹 Expand dataset size for improved generalization  
🔹 Integrate additional behavioral and psychological features  
🔹 Test ensemble models combining CNN, LSTM, and GRU  

## **Repository Contents**  
📁 **Data Preprocessing** - Cleaning and preparing the dataset  
📁 **Model Training** - Implementation of CNN, LSTM, and GRU models  
📁 **Evaluation Metrics** - Performance analysis and comparison  

---

### 🚀 **Interested? Explore the Project Here:**  
🔗 **GitHub Repo:** [Tobacco Usage Cessation Prediction](https://github.com/akindream/Smoking-Cessation)  
🔗 **Medium:** [Tobcco Usage Cessation Prediction](https://medium.com/@akindream/predicting-tobacco-cessation-success-with-artificial-neural-networks-282abbcdacd0)
🔗 **Linkedin** [Tobacco Usage Cessation Prediction](https://www.linkedin.com/posts/ernest-braimoh-29284b141_ai-machinelearning-deeplearning-activity-7306287492310130688-wqZ8?utm_source=share&utm_medium=member_desktop&rcm=ACoAACJ5f84BSF16YQBlNnzy86sMhIc99PdU8l0)
