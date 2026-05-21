# dual-attention-mechanism
Dual-Attention Network with Gated Dynamic Fusion for Multimodal Knowledge Graph Completion
dual-attention-mkgc/
│
├── README.md
├── requirements.txt
├── train.py
├── test.py
├── config.py
│
├── models/
│   ├── gnn_model.py
│   ├── gat_model.py
│   ├── intra_attention.py
│   ├── cross_attention.py
│   ├── dual_attention.py
│   ├── gating_fusion.py
│   ├── transformer_encoder.py
│   ├── scoring.py
│
├── utils/
│   ├── data_loader.py
│   ├── metrics.py
│   ├── losses.py
│
├── experiments/
│   ├── ablation.py
│   ├── parameter_search.py
│
└── figures/
