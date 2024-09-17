# Product Attribute Extraction from Images

## Team: The_Techies  
- Nand Rabadiya <a href="https://github.com/NandRabadiya" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=github" width="20" height="20" /></a>
<a href="https://www.linkedin.com/in/nand-rabadiya/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=linkedin" width="20" height="20" /></a>

- Venu Virparia <a href="https://github.com/venuvirparia" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=github" width="20" height="20" /></a>
  <a href="https://www.linkedin.com/in/venu-virparia/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=linkedin" width="20" height="20" /></a>
    
- Smit Shah <a href="https://github.com/smitshah084" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=github" width="20" height="20" /></a>
  <a href="https://www.linkedin.com/in/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=linkedin" width="20" height="20" /></a>
  
- Diya Prajapati <a href="https://github.com/diyaprajapati" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=github" width="20" height="20" /></a>
  <a href="https://www.linkedin.com/in/diya-prajapati-453858267/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=linkedin" width="20" height="20" /></a>
---

### 1. **Introduction**  
The aim of this project is to develop a machine learning model that can extract essential product attributes such as **weight, volume, voltage**, and **dimensions** directly from product images. This automation is particularly beneficial for industries like **e-commerce** and **healthcare**, where accurate product details are often lacking in textual descriptions. By extracting this data from images, we can improve product cataloging and accelerate the onboarding process for new items in digital marketplaces.

---

### 2. Step-by-Step Approach
-  **Installing Dependencies**: Install libraries such as `datasets`, `flash_attn`, `timm`, and `einops` for data handling and image processing.
-  **Loading the Dataset**: Load the `DocumentVQA` dataset, split it into training, validation, and test sets, and format it for model training.
-  **Loading the Model and Processor**: Use Microsoft's Florence-2 model, a vision-language model, to process images and text for training and inference.
-  **Image Preprocessing**: Prepare images by converting them to a compatible format and RGB mode.
-  **Inference**: Test the model's ability to predict attributes from images before fine-tuning.
-  **Fine-tuning Setup**: Construct and preprocess the dataset for model fine-tuning, then configure the optimizer and learning rate scheduler.
-  **Training and Validation**: Eecute the training loop while freezing the image encoder to improve efficiency, and monitor the model's performance on the validation set.
-  **Model Saving and Deployment**: Save the fine-tuned model and deploy it on the Hugging Face Hub for public access.

---

### 3. **Conclusion**  
  - Objective: Fine-tune Microsoft's Florence-2 model for Document Visual Question Answering.
  - Approach: After preparing the dataset, the model is fine-tuned by freezing the image encoder and training the text encoder.
  - Output: A fine-tuned model is pushed to the Hugging Face Hub for public use.

---

### 4. **Future Development**  
   - Model Refinement: Improve accuracy with larger datasets and more sophisticated architectures.
   - Deployment: Implement the model in real-world environments for live product cataloging.
   - Future work will focus on enhancing error handling, prediction accuracy, and scalability.

---

### 5. **Suggestions and Contact**  
We welcome any suggestions for improving the model or exploring new features. Please feel free to reach out to us!

