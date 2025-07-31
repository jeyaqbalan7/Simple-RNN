# Deep Learning 


##  Project Overview

This project uses a deep learning model built with TensorFlow to classify movie reviews as positive or negative. The model was trained on a dataset of IMDB reviews and can predict the sentiment of any new movie review entered by the user. The Streamlit app makes it easy to interact with the model through a user-friendly interface. 

---

## How to Run Locally (in Google Colab)
1.Install Streamlit:
```
!pip install streamlit -q
```
2.Check your public IP (optional):
```

!wget -q -O - ipv4.icanhazip.com
```
3.Run the Streamlit app and tunnel it using LocalTunnel:
```
!streamlit run app.py & npx localtunnel --port 8501
```
##  File

- **ML_PT(DEEP_L_2).ipynb**  
  The main notebook that walks through a deep learning pipeline including:
  - Data preprocessing
  - Model creation
  - Training
  - Evaluation

---

##  Key Topics Covered

- Neural Networks with Keras/TensorFlow  
- Activation Functions  
- Model Architecture Definition  
- Compilation and Training  
- Evaluation and Metrics  
- Overfitting & Regularization  
- Visualization with Matplotlib/Seaborn  

---

## Tech Stack

- **Language**: Python 3.x  
- **Environment**: Jupyter Notebook  
- **Libraries**:
  - TensorFlow / Keras  
  - NumPy  
  - Pandas  
  - Matplotlib  
  - Seaborn  

---

## Output
<img width="1152" height="593" alt="image (1)" src="https://github.com/user-attachments/assets/fcd9db34-b467-41dc-b0e4-8572f7591578" />


##  Conclusion

This project serves as a hands-on demonstration of building and evaluating deep learning models using TensorFlow and Keras. By working through this notebook, you’ll gain practical experience with model architecture design, training, and performance evaluation. It’s a solid foundation for anyone looking to deepen their understanding of applied machine learning and deep learning techniques.



