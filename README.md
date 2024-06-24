# hackaton
# hackathon is a competition by Analytics Vidhya. It involves detecting a series of fraudulent photographs of claims for an insurance company. It is a clear example of imbalanced data. I have used an ensemble model of simple CNN model and a pretrained model.
# I have used weighted loss function to solve imbalanced data classification problems.
# I have applied a 9:1 ratio between positive and negative cases, but the result was not very satisfactory
# probably the result would have been better if I had calculated the weights using:        weight_for_class_i = total_samples / (num_samples_in_class_i * num_classes)
#I have used Kaggle Notebooks because they provide more GPU resources than google.colab
