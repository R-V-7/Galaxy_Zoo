Here’s a concise and accessible README description for your project:

---

## Galaxy Zoo Classification with MobileNetV2 and LoRA  

This project focuses on classifying galaxies using the **Galaxy Zoo dataset** with MobileNetV2, a lightweight and efficient convolutional neural network. Three main approaches were implemented:  

1. **Feature Extraction**:  
   MobileNetV2 was used as a feature extractor with pre-trained weights (ImageNet). The model's base layers were frozen, and a custom classifier was added on top.  

2. **Fine-Tuning**:  
   Building on the previous step, the base layers of MobileNetV2 were unfrozen to fine-tune the entire network for improved performance.  

3. **LoRA (Low-Rank Adaptation)**:  
   LoRA was applied to optimize the fine-tuning process. This technique reduces the number of trainable parameters, making the model more efficient while maintaining accuracy.  

The goal was to explore lightweight and efficient deep learning techniques for galaxy classification while balancing computational cost and performance.  

---  
