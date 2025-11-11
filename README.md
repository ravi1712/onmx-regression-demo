Auto Price Prediction (Neural Networks + ONNX + Web Demo)
#  Auto Price Prediction using Neural Networks and ONNX

This project predicts automobile prices based on technical and categorical attributes from the UCI “Automobile” dataset.  
It trains multiple neural network architectures and a Random Forest model, compares their performance, and deploys the best model using **ONNX** on **GitHub Pages** for browser-based inference.

---

##  Features
- Data preprocessing (imputation, scaling, one-hot encoding)
- Three neural network architectures: SimpleNN, DeepNN, WideNN
- Random Forest model for comparison
- R² score and loss visualization
- Export to **ONNX** format
- Browser-based demo using **ONNX Runtime Web**

---

##  Requirements
Install dependencies before running the code:
```bash
pip install pandas numpy scikit-learn torch matplotlib seaborn onnx onnxruntime
 Result
| Model         | R² Score |
| ------------- | -------- |
| Simple NN     | ~0.85    |
| Deep NN       | ~0.88    |
| Wide NN       | ~0.86    |
| Random Forest | ~0.90    |
