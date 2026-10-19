# Deep Learning & Computer Vision

Neural network coursework comparing convolutional and fully connected networks, image recognition and transfer learning.

**Author:** Mohammed Alaa Eddine GUERBOUZ  
**University:** University of Ghardaia, Department of Mathematics and Computer Science  
**Academic period:** 2023–2025 master coursework where confirmed; some items have unverified dates  
**Portfolio curated:** 2026

## What this work demonstrates

This repository preserves practical assignments and projects completed during the academic programme, reorganized by problem rather than original archive names. It contains actual submitted code and reports, enhanced notebook introductions and descriptive folder names. It is not a claim of recent creation or independent production deployment.

## Project catalog

### 2023-2024 · projects

| Work | Problem addressed |
|---|---|
| [CIFAR-10 CNN versus FCNN (Master 1)](projects/2023-2024/cifar10-cnn-vs-fcnn-m1/README.md) | Compare neural-network architectures on ten image categories. |
| [CIFAR-100 CNN versus FCNN (Master 1)](projects/2023-2024/cifar100-cnn-vs-fcnn-m1/README.md) | Explore 100-class image classification with neural networks. |
| [Fashion-MNIST Convolutional Classifier (M1 Series)](projects/2023-2024/fashion-mnist-cnn-m1/README.md) | Recognize clothing types from grayscale images. |
| [MNIST: Dense and Convolutional Models (M1 Series)](projects/2023-2024/mnist-cnn-vs-fcnn-m1/README.md) | Compare densely connected networks to convolutional networks on handwritten digits. |
### 2024-2025 · projects

| Work | Problem addressed |
|---|---|
| [Cats versus Dogs: Transfer Learning](projects/2024-2025/cats-vs-dogs-transfer-learning/README.md) | Classify cat and dog photographs with a pretrained convolutional feature extractor. |
| [CIFAR-10: CNN versus FCNN](projects/2024-2025/cifar10-cnn-vs-fcnn/README.md) | Compare dense and convolutional models on ten image classes. |
| [CIFAR-100 CNN Classification](projects/2024-2025/cifar100-cnn/README.md) | Learn a multiclass image classifier for one hundred image categories. |
| [CNN Classification Exercises](projects/2024-2025/cnn-exercises-and-report/README.md) | Experiment with convolutional architectures for image datasets. |
| [Fashion-MNIST Image Classification](projects/2024-2025/fashion-mnist-cnn/README.md) | Predict clothing categories from small grayscale images. |
| [MNIST: CNN versus Fully Connected Networks](projects/2024-2025/mnist-cnn-vs-fcnn/README.md) | Classify handwritten digits and compare convolutional and dense neural networks. |
### undated · projects

| Work | Problem addressed |
|---|---|
| [CNN Exercises: Earlier Notebook Variant](projects/undated/cnn-exercises-original-variant/README.md) | Preserve a separately submitted notebook variant for image classification practical work. |

## Working with the notebooks

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
jupyter lab
```

Open and run a notebook from its project folder so relative paths work. Some datasets are not included; each experiment README identifies missing local or remotely downloaded inputs. GPU-enabled TensorFlow, older APIs and Colab-specific shell commands may require compatible environments. R coursework also requires R/RStudio and packages used by the original code.


## Notes about the original sources

- Original notebook **code cells were not refactored or rewritten**. A clearly labeled Markdown introduction was added to notebooks for provenance and readability.
- Original DOCX reports and supporting images were only renamed and moved; their content remains byte-for-byte identical.
- Some notebooks rely on missing datasets, local Windows paths, network downloads, old libraries or GPU resources and **have not been rerun or benchmarked**. No unverified accuracies are claimed.
- Notebook years in the original headers are usually **Master 1 2023–2024** or **Master 2 2024–2025**. Where the period is inferred from a neighboring numbered TP series or not explicit in a particular source notebook, the project README says so. Other dates are sourced from the original notebook headers.
- Review licenses/redistribution rights for third-party datasets before pushing publicly. Large binary datasets, generated artifacts and serialized R workspaces should not be committed without review.

For original filename-to-new-path tracking, see `PORTFOLIO_INVENTORY.csv` at the top level of the consolidated download (not included in this individual repository).
