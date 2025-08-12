# GPU-Operations-in-PyTorch
# PyTorch GPU-Accelerated Data Processing

This project demonstrates how to accelerate a PyTorch model training pipeline by leveraging the GPU to process data efficiently. It includes dataset loading, GPU transfers, model training, evaluation, and overall data-to-GPU dataflow.

---

##  Features

- Leverages GPU (`cuda`) to process both model and data efficiently.
- Uses `Dataset` and `DataLoader` abstractions for batch loading.
- Demonstrates per-batch data transfer to GPU and training.
- Includes model evaluation logic using `torch.no_grad()` on GPU-loaded data.
- Easy-to-understand structure that can scale to complex pipelines.

---

##  How It Works

1. **Dataset & DataLoader**: Batches data using PyTorch `DataLoader`.
2. **GPU Acceleration**: Moves both model and batch data to the GPU using `to(device)`.
3. **Training Loop**:
   - Forward pass
   - Loss computation and backward pass
   - Weight updates
4. **Evaluation**: Uses `torch.no_grad()` to compute accuracy without tracking gradients.

---


---
Author

Saniya Chhabra❤️

---
License
This project is licensed under the MIT License.
