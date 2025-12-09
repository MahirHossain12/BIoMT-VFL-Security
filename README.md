BIoMT-VFL: Blockchain-Secured Vertical Federated Learning for IoMT

## 💡 Overview

This project introduces **BIoMT-VFL**, a framework that integrates **Blockchain** with **Vertical Federated Learning (VFL)** to guarantee **security and privacy** for collaborative machine learning in the Internet of Medical Things (IoMT).

It enables multiple healthcare institutions to train models collaboratively on shared patient data (with different feature sets) **without sharing raw data**, while using the blockchain to provide **auditable, tamper-proof security** for model updates.

### Core Technologies

  * **Vertical Federated Learning (VFL):** Enables feature-disparate data silos to learn together privately.
  * **Blockchain (e.g., Hyperledger):** Secures model aggregation and participant interactions.
  * **IoMT:** Focuses on sensitive medical data and secure collaborative training.

## 🚀 Quick Start

### Prerequisites

  * Python 3.8+
  * Docker (for Blockchain network setup)

### Installation

1.  **Clone & Setup:**

    ```bash
    git clone https://github.com/YourUsername/BIoMT-VFL.git
    cd BIoMT-VFL
    pip install -r requirements.txt
    ```

2.  **Start Blockchain Network:**

    ```bash
    ./scripts/start_blockchain.sh
    ```

3.  **Run VFL Simulation:**

    ```bash
    python src/run_vfl_experiment.py
    ```

    *(This script handles the server, client, and secure aggregation process.)*

## 📚 Structure

| Directory | Purpose |
| :--- | :--- |
| `src/vfl/` | Core VFL implementation (model definition, security protocols). |
| `src/blockchain/` | Smart contracts and ledger interaction logic. |
| `data/` | Synthetic/Sample IoMT datasets for testing. |
| `config/` | System and model configuration files. |

## 🤝 Contributing

We welcome contributions\! Please refer to the `CONTRIBUTING.md` (if available) or simply open an Issue or Pull Request.

## ⚖️ License

MIT License. See `LICENSE.md` for full details.
