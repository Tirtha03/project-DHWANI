# PROJECT DHWANI 2.4 — Research Methodology

## 1. Introduction

The research methodology of PROJECT DHWANI explores the use of acoustic sensing, digital signal processing, and artificial intelligence for environmental signal analysis.

The proposed methodology is organized into a sequence of research stages, beginning with signal acquisition and ending with computational evaluation.

The objective is to establish a reproducible framework for studying environmental acoustic patterns.

## 2. Research Objectives

The primary objectives are:

1. Study environmental acoustic signal characteristics.
2. Investigate digital signal processing techniques.
3. Explore meaningful acoustic feature extraction.
4. Evaluate machine-learning approaches for environmental sound classification.
5. Study computational efficiency for edge-based processing.
6. Establish a controlled model-validation framework.

## 3. Research Workflow

The proposed workflow consists of six stages:

### Stage 1 — Data Acquisition

Collect suitable environmental audio samples from authorized and openly available datasets.

Potential categories:

- Rainfall
- Wind
- Flowing water
- Bird vocalizations
- Ambient environmental sounds

Record relevant metadata such as:

- Sample rate
- Recording duration
- Recording environment
- Audio format
- Dataset source

### Stage 2 — Signal Preprocessing

Prepare the acquired audio for computational analysis.

Research techniques may include:

- Noise characterization
- Amplitude normalization
- Audio segmentation
- Filtering
- Sampling-rate standardization

### Stage 3 — Feature Extraction

Investigate features that describe the characteristics of environmental audio.

Potential features:

| Feature | Purpose |
|---|---|
| RMS Energy | Signal energy estimation |
| Zero-Crossing Rate | Signal variation |
| Spectral Centroid | Spectral brightness |
| Spectral Bandwidth | Frequency distribution |
| MFCC | Compact representation of audio characteristics |
| Spectrogram | Time-frequency visualization |

### Stage 4 — Machine Learning

Explore suitable machine-learning models for environmental sound classification.

Potential research approaches:

- Support Vector Machine
- Random Forest
- K-Nearest Neighbours
- Convolutional Neural Networks

Model selection should depend on dataset size, computational requirements, and validation performance.

### Stage 5 — Edge Computing Research

Investigate whether trained models can be optimized for resource-constrained computing environments.

Potential research areas:

- Model quantization
- Memory optimization
- Inference latency
- Computational efficiency
- Power consumption

### Stage 6 — Evaluation

Evaluate the model using a controlled and reproducible testing process.

The evaluation should include:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix
- Inference time
- Model size

No performance claims should be made until actual experiments have been completed.

## 4. Digital Signal Processing

Digital Signal Processing (DSP) is an important research area within DHWANI.

The project investigates how environmental audio signals can be transformed into useful numerical representations.

The research may include:

- Time-domain analysis
- Frequency-domain analysis
- Short-Time Fourier Transform
- Spectrogram generation
- Mel-frequency cepstral coefficients

## 5. AI/ML Research

The AI research component focuses on identifying patterns in environmental audio.

A reproducible machine-learning workflow should include:

1. Dataset preparation
2. Data cleaning
3. Feature extraction
4. Train-test separation
5. Model training
6. Hyperparameter evaluation
7. Model validation
8. Performance reporting

Dataset leakage must be avoided when separating training and testing samples.

## 6. Edge AI Research

Edge AI investigates the possibility of running computational models locally rather than relying entirely on cloud infrastructure.

Research parameters include:

- Model memory footprint
- Processing latency
- CPU utilization
- Energy consumption
- Classification performance

## 7. Experimental Design

Experiments should use documented datasets and controlled conditions.

Each experiment should record:

- Experiment ID
- Dataset version
- Model version
- Parameters
- Software environment
- Evaluation metrics
- Results
- Limitations

## 8. Validation Metrics

| Metric | Purpose |
|---|---|
| Accuracy | Overall correct predictions |
| Precision | Reliability of positive predictions |
| Recall | Coverage of relevant samples |
| F1-score | Balance between precision and recall |
| Confusion Matrix | Classification error analysis |
| Inference Time | Computational speed |
| Model Size | Storage requirements |

## 9. Research Limitations

Potential research limitations include:

- Background environmental noise
- Dataset imbalance
- Differences between recording environments
- Limited training data
- Model generalization
- Hardware computational constraints

These limitations must be evaluated experimentally.

## 10. Future Research

Future research directions include:

- Larger environmental audio datasets
- Improved feature extraction
- Lightweight classification models
- Multi-modal environmental data analysis
- Embedded inference experimentation
- Controlled real-world environmental validation

## 11. Conclusion

The proposed methodology establishes a structured research pathway for investigating environmental acoustic analysis using digital signal processing and artificial intelligence.

The methodology will evolve through reproducible experiments, documented findings, and evidence-based technical improvements.

---

**PROJECT DHWANI 2.4**

Research Documentation | Methodology
