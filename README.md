## Guard - Artificial Criminal Mind Detection Using Machine Learning
Guard is an AI-powered system designed to analyze behavioral patterns and identify potential criminal intent using machine learning techniques. The project leverages advanced algorithms to assess various factors such as facial expressions, speech patterns, and psychological traits to detect suspicious activities. The goal is to assist law enforcement in early threat detection and enhance public safety while maintaining ethical AI practices.
## About
Guard - Artificial Criminal Mind Detection Using Machine Learning is an AI-powered system that leverages machine learning and deep learning techniques to analyze behavioral patterns and detect potential criminal intent. It utilizes algorithms like ARIMA for time-series analysis of behavioral data and LSTM for sequential pattern recognition in speech and movements. The system evaluates facial expressions, speech patterns, and psychological traits to identify suspicious activities. With Chi-Square feature selection optimizing data processing and NLP enhancing speech analysis, this project aims to assist law enforcement in early threat detection while ensuring ethical AI practices for security and crime prevention.

## Features 
- Implements advanced neural network methods like LSTM for sequential pattern recognition.  
- A framework-based application designed for real-time deployment in security systems.  
- High scalability, enabling efficient processing of large behavioral datasets.  
- Optimized time complexity for quick analysis and threat detection.  
- Integrates a chatbot response model using JSON data format for interactive security alerts.  
- Utilizes ARIMA for time-series analysis of behavioral trends and crime patterns.  
- Employs Chi-Square feature selection for improved data preprocessing and accuracy.

## Requirements 
- **Operating System:** Requires a 64-bit OS (Windows 10/11 or Ubuntu) for compatibility with deep learning frameworks.  
- **Development Environment:** Python 3.6 or later is required for implementing AI models.  
- **Deep Learning Frameworks:** TensorFlow and Keras for model training, with LSTM and ARIMA for sequential data analysis.  
- **Machine Learning Libraries:** scikit-learn for feature selection (Chi-Square) and classification tasks.  
- **Image & Speech Processing:** OpenCV for facial analysis, NLP libraries for speech pattern recognition.  
- **Version Control:** Git for collaborative development and efficient code management.  
- **IDE:** VSCode for coding, debugging, and seamless integration with version control.  
- **Additional Dependencies:** TensorFlow (2.4.1+), TensorFlow GPU (for acceleration), OpenCV, and Mediapipe.

## System Architecture
![image](https://github.com/user-attachments/assets/eb70716a-bc9b-49ca-bc0f-c6ab735b9046)

## Equations used:
\section{Equations Used}

\subsection{Decision Tree Classifier}
The Decision Tree algorithm follows:
\begin{equation}
    Gini(D) = 1 - \sum p_i^2
\end{equation}
where \( Gini(D) \) measures impurity and \( p_i \) is the probability of class \( i \). The tree splits data by selecting features that minimize impurity.

\subsection{Random Forest Classifier}
Random Forest combines multiple Decision Trees:
\begin{equation}
    RF(X) = \frac{1}{N} \sum_{i=1}^{N} T_i(X)
\end{equation}
where \( T_i(X) \) is the prediction from each tree, and \( N \) is the total number of trees.

\subsection{K-Nearest Neighbors (KNN)}
KNN classifies based on distance:
\begin{equation}
    d = \sqrt{\sum (x_i - y_i)^2}
\end{equation}
where \( x_i \) and \( y_i \) are feature values of two points.

\subsection{Model Evaluation Metrics}
\textbf{Accuracy:}
\begin{equation}
    Accuracy = \frac{TP + TN}{TP + TN + FP + FN}
\end{equation}

\textbf{Precision:}
\begin{equation}
    Precision = \frac{TP}{TP + FP}
\end{equation}

\textbf{Recall:}
\begin{equation}
    Recall = \frac{TP}{TP + FN}
\end{equation}

\textbf{F1-score:}
\begin{equation}
    F1 = 2 \times \frac{Precision \times Recall}{Precision + Recall}
\end{equation}

## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Name of the output

![Screenshot 2023-11-25 134037](https://github.com/<<yourusername>>/Hand-Gesture-Recognition-System/assets/75235455/8c2b6b5c-5ed2-4ec4-b18e-5b6625402c16)

#### Output2 - Name of the output
![Screenshot 2023-11-25 134253](https://github.com/<<yourusername>>/Hand-Gesture-Recognition-System/assets/75235455/5e05c981-05ca-4aaa-aea2-d918dcf25cb7)




## Results and Impact


The Guard - Artificial Criminal Mind Detection system demonstrates promising results in analyzing behavioral patterns for potential threat detection. Using LSTM and ARIMA, it effectively identifies sequential patterns in speech and movement, improving detection accuracy. The Chi-Square feature selection enhances model efficiency by prioritizing key behavioral indicators. Real-time analysis of facial expressions and speech patterns ensures quick response times, making it a valuable tool for security applications.  

This system has the potential to assist law enforcement in early crime prevention, reduce false alarms, and improve surveillance accuracy, contributing to a safer and more secure society.
## Articles published / References
[1] S. D. P. Mendonça, Y. P. D. S. Brito, C. G. R. D. Santos, R. D. A. D. Lima, T. D. O. D. Araújo, and B. S. Meiguins, "Role of Artificial Intelligence in the Crime Prediction and Pattern Analysis," in Springer Al & Law, 2024.

[2] P. A. Osorio-Marulanda, G. Epelde, M. Hernandez, I. Isasa, N. M. Reyes, and A. B. Iraola, "Al in Crime Prediction and Prevention, in IEEE Access, vol. 12, pp. 88048-88074, 2024.

[3] A. Williams and B. Kovalerchuk, "CrimeAlarm: Towards Intensive Intent Dynamics in Fine-grained Crime Prediction, in 2024 28th International Conference on Al and Law (ICAIL), Coimbra, Portugal, 2024.

[4] P. Singh, A. Necholi, and W. Moreno, "Crime Prediction Using Machine Learning and Deep Learning: A Systematic Review and Future Directions," 2023 IEEE 3rd International Conference on Al Applications, Chiclayo, Peru, 2023.

[5] P. A. Apellániz, A. Jiménez, B. Arroyo Galende, J. Parras, and S. Zazo, "Crime Prediction Using Machine Learning with a Novel Crime Dataset," in IEEE Access, vol. 12, pp. 103895-103907, 2022.

[6] R. Akiyama et al., "Crime Forecasting Using Al-Based Behavioral Modeling, 2022 3rd International Conference on Artificial Intelligence and Data Sciences (AIDAS), IPOH, Malaysia, 2022.

[7] R. N. V., K. Akshaya, P. Ramadevi, and M. Y. Reddy, "Crime Forecasting: A Machine Learning and Computer Vision Approach to Crime Prediction and Prevention, 2021 International Conference on Computer Vision and Data Science (CVDS), Coimbatore, India, 2021

