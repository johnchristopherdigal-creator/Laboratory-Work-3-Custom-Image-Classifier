# Laboratory-Work-3-Custom-Image-Classifier

google colab link: https://colab.research.google.com/drive/1F_d88cHJtokb8ykV_dIaEQpwJlK_i9q5?usp=drive_link

## PART 4: Compare Results (Before vs After)
## Guide Questions (Student Explanation & Reflection) 
Students must answer: 
## Visualization & Overfitting 
1. What signs indicated overfitting in your first model? I noticed overfitting when the training accuracy kept getting higher, but the validation accuracy stopped improving. This showed that the model was memorizing the training data instead of learning patterns.
2. How did data augmentation affect validation accuracy? Data augmentation helped improve validation accuracy because the model was trained using different image variations like flips and rotations, making it better at handling new images.
## Model Improvement 
3. What is the purpose of dropout layers?  Dropout layers help prevent overfitting by randomly disabling some neurons during training. This forces the model to learn more useful and general features.
4. Why does data augmentation improve generalization? Data augmentation improves generalization because it increases image variety without needing more data, helping the model adapt better to unseen images.
## Performance Comparison 
5. Compare accuracy before and after improvements. After applying improvements, the model achieved higher validation accuracy and showed more stable performance compared to the first model.
6. Which technique contributed most to improvement? Data augmentation contributed the most because it gave the model more diverse training examples, which improved learning and reduced overfitting.
## Deployment & Application 
7. Why is saving the model important?  Saving the model is important because it allows the trained system to be reused anytime without training it again. 
8. How can this model be deployed in a real-world system? This model can be deployed in mobile or web applications for tasks like plant identification, disease detection, or other image classification systems used in real-world environments.

