# Project Interfaces

## Model Dimensions
- Image feature dimension: 512
- Clinical feature dimension: 64
- Fusion input: 576
- Fusion output: 256

## Federated Learning
- Cross-Silo Federated Learning
- Flower
- FedAvg
- Prototype clients: 3
- Non-IID split: Dirichlet
- Alpha: 0.5

## Batch Format

```python
batch = {
    "image": ...,
    "clinical": ...,
    "label": ...
}
