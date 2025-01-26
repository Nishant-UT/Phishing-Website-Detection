# Phishing-Website-Detection

The implemented solution leverages deep learning techniques for the robust detection of phishing websites, addressing the critical challenge of online security. The code begins with data loading and preprocessing, using the pandas library to handle the dataset ('dataset_phishing.csv'). This dataset's structure is explored, revealing key features like 'url' and the target variable 'status.' The target variable is encoded using LabelEncoder and one-hot encoding for effective model training.

Moving on to model architecture, a sequential neural network is constructed using the Keras library. It incorporates layers such as Embedding, LSTM, GRU, Dropout, and Dense, forming a sophisticated architecture capable of capturing sequential patterns and preventing overfitting. The model is compiled with categorical cross-entropy loss and the Adam optimizer before undergoing training on the prepared dataset.

Also, the script demonstrates the training and evaluation of a Decision Tree classifier on a binary classification problem, providing both numerical and visual insights into the model's performance and the dataset's characteristics.

Model evaluation is performed using the test set, generating a confusion matrix for a visual representation of the model's performance. Additionally, a correlation matrix heatmap is created to unveil underlying relationships among numeric features in the dataset. The distribution of the target variable ('status') is depicted through a count plot, offering insights into the dataset's class distribution.

The documentation highlights the visualizations' importance in understanding the dataset and model performance. A classification report is printed to provide a comprehensive overview of the model's accuracy, precision, recall, and F1 score. To enhance user interaction, the model accepts website URLs as input, enabling real-time predictions and making it a practical tool for assessing potential phishing risks. This holistic approach to phishing detection, blending deep learning with traditional data visualization techniques, creates a robust and informative solution for online security.
