Various models are constructed with PyTorch and scikit-learn to organize BERT encoded textual features, VGGish encoded acoustic features, and ResNet encoded visual features into classified emotions using the IEMOCAP dataset.

Models structured around GRUs and SVCs are compared empirically.

This project revolves around multimodal emotion classification, incorporating data from three distinct data types via multimodal fusion: vision, speech, and text. The goal is to detect and categorize human emotions into four primary classes, utilizing an extensive array of data processing, feature extraction, and machine learning techniques. Different methods for pooling and temporal modeling are employed to address the temporal dimension in audio and visual files. Various classifiers are applied for emotion classification, with the most effective parameters selected via Grid Search. 

The project also addresses class imbalance and applies both early and late fusion techniques to yield optimal results. A thorough evaluation and interpretation of the unimodal and multimodal classification tasks informs better performance.
