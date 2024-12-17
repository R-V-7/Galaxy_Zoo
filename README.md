

## Galaxy Zoo Classification with MobileNetV2 and LoRA  

This project focuses on classifying galaxies using the **Galaxy Zoo dataset** with MobileNetV2, a lightweight convolutional neural network. Three main approaches were implemented:  

1. **Feature Extraction**:  
   MobileNetV2 was used as a feature extractor with pre-trained weights (ImageNet). The model's base layers were frozen.  

2. **Fine-Tuning**:  
   The last 10 layers of MobileNetV2 were unfrozen to fine-tune the model for improved performance.  

3. **LoRA (Low-Rank Adaptation)**:  
   LoRA was applied to further optimize fine-tuning by injecting low-rank adapters into the model's trainable layers. This significantly reduces the number of parameters being updated during training. LoRA makes the model adaptable without the need for full fine-tuning, offering a balance between performance and computational efficiency.  

The goal was to explore lightweight and efficient deep learning techniques for galaxy classification using modern methods like fine-tuning and parameter-efficient training with LoRA.

