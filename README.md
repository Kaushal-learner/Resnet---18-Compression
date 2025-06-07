# Resnet---18-Compression
This project applies multiple model compression techniques to the ResNet-18 architecture to reduce size and inference time while preserving model performance.
# Techniques Used 
**Pruning** – Removed less significant weights to reduce model complexity.
**Quantization** – Reduced model precision from 32-bit to 8-bit for smaller size and faster computation.
**Knowledge Distillation** – Transferred knowledge from a larger model (teacher) to a smaller compressed student model.
## Results

| Metric            | Value           |
|-------------------|-----------------|
| **Training Accuracy** | 45.89%          |
| **Model Size**        | 22.64 MB        |
| **Average Latency**   | 3.09 ms         |
