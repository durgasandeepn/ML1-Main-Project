**Speech Emotion Recognition from Audio (ML I Final Project)**

Group Project — Josh Parker, Durga Sandeep Varma Namballa, Charles Winters, Jacob Schertz

Overview: Machine learning system to automatically detect human emotions from speech audio, aimed at enabling more empathetic AI systems (e.g., AI therapists, conversational agents that respond appropriately to emotional cues).

Dataset: CREMA-D — 7,442 voice clips from 91 actors, including pre-extracted features (gender, emotion, accent) and raw audio files.

Approach
Extracted acoustic features (primarily MFCCs) to supplement the dataset's existing metadata
Trained two complementary classifiers:
Support Vector Machine (SVM) — strong track record for speech emotion classification
Random Forest Ensemble — provides feature importance to identify which acoustic cues drive emotion predictions
Tuned both models via 5-fold cross-validation
Evaluation

Assessed models on both predictive performance and computational efficiency:

Accuracy and precision on unseen test data
Training time per fold and prediction time per sample, to evaluate real-world deployment feasibility
k-fold cross-validation (k=5–10) used throughout to ensure robust, generalized results and mitigate overfitting

Tech stack: Python, scikit-learn (SVM, Random Forest), audio feature extraction (MFCCs)


[View the Project in Document format](FinalProjectAnalysis.pdf)

[View the Project Details](project_checkin.pdf)

