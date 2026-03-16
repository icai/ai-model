# ai-model


A centralized repository for storing and distributing AI model releases — specifically PyTorch `.pt` weight files.

This repository is intended as the authoritative source for model artifacts used in projects and deployments.

---

## 📦 Current Release

We currently have one official model release:

➡️ **[model · Release on GitHub](https://github.com/icai/ai-model/releases/tag/model)**

Download model artifacts directly from the release page.


## AI Models

| Model | Download |
|------|------|
| lama | ![](https://img.shields.io/github/downloads/icai/ai-model/model/lama.pt) |
| u2net | ![](https://img.shields.io/github/downloads/icai/ai-model/model/u2net.pt) |

---

## 📁 Repository Purpose

This repo is specifically designed to:

* Host AI model weight files (`.pt`)
* Provide versioned releases
* Separate large binaries from application source code
* Track model changes over time in a structured way

Model files are distributed via **GitHub Releases** — not stored directly in the main branch.

---

## 🚀 How to Use

### 🪟 1. Download Model File

Go to the release above and download the `.pt` file.

### 🐍 2. Load with PyTorch

Example:

```python
import torch

model = torch.load("path/to/model.pt", map_location="cpu")
model.eval()
```

Modify this code to match your model class definition and architecture.

---


## 🤝 Contributing

If you want to add or update a model:

1. Fork the repository
2. Prepare your model weight files (`.pt`)
3. Create a new **GitHub Release**
4. Add release notes (including model details)
5. Submit a Pull Request (optional, if not changing structure)

---

## ⚠️ Distribution & Licensing

* Ensure you have rights to publish the model files you upload.
* If specific license terms apply to a model, include them in the release notes.
* This repository itself follows MIT-style documentation principles.

