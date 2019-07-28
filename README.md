# Audio-Signal-Source-Recognition
Audio Signal Source Recognition (Deep Neural Networks)

With the continued exponential growth of the digital age, the importance of providing meaning to data has grown considerably. This project focuses on recognizing sources of musical signals embedded within time-series data. The problem has been divided into two phases. 

In the first phase, we performed single instrument recognition using existing machine learning techniques and neural network architectures developed specifically for musical signal processing. In the second phase, we incorporated advanced neural network architectures and techniques developed for applications outside the scope of musical audio processing and applied them to recognize simultaneously playing instruments in an audio file. 

Our single instrument recognizer utilized context specific \gls{cnn} filters and achieved an accuracy score of 98.5$\%$ which out performed previously developed models. Our multiple instrument recognizer utilized techniques such as transfer learning and model ensembling to optimize overall performance. We borrowed concepts from fields such as \gls{nlp} and medical processing to build our final model, which achieved an F1 score of 85.5$\%$. Furthermore, we also introduced a custom loss function designed specifically to train networks to perform multi-labeled classification tasks. 
