# 👋 Hi, I'm Sathya Narayanan (@sathya8998)

**Deep Learning Researcher | Multimodal Fusion Specialist | Bio-Medical AI Engineer**
*Master's graduate actively seeking PhD opportunities in multimodal biomedical AI.*

I build high-stakes AI systems that bridge the gap between biological signals and clinical insights. My work is organized into four specialized pillars: **Human Biomechanics**, **Neuroengineering**, **Medical Imaging**, and **Bioinformatics**.

---

## 🦵 Pillar I: Human Biomechanics & Robotics
*Decoding movement and intent for rehabilitation and autonomous systems.*

* **[Master's Thesis] [Gait Phase Prediction](https://github.com/sathya8998/Gait_Phase_Prediction):** Decoding gait cycles from **High-Density EMG** and Kinematic fusion using deep temporal models for prosthetic/exoskeleton control.
* **[Gait Scoring (CVPR 2026)](https://github.com/sathya8998/Spatio-Temporal-Skeleton-Fusion-for-Clinical-Gait-Scoring):** Biomechanical **ST-GCN** for fine-grained gait analysis in pediatric Cerebral Palsy.
* **[Sign Language Motion Generation](https://github.com/sathya8998/Hierarchical-Text-to-Sign-Motion-Generation-with-RVQ-VAE-and-Transformer):** A two-stage Masked + Residual Transformer architecture generating high-fidelity sign motion from text using **RVQ-VAE** discrete tokens.
* **[Terrain-Aware Navigation](https://github.com/sathya8998/Multi-Modal-Fusion-and-Multi-Task-Learning-for-Terrain-Aware-Navigation):** Robotic perception fusing **RGB, PointNet (LiDAR), and IMU** for autonomous movement.
* **[Muscle Morphometry](https://github.com/sathya8998/Skeletal-Muscle-Architecture-Estimation-using-EfficientNet-and-Grad-CAM):** Automating ultrasound-based biomarker extraction (Pennation Angle, Fascicle Length).
* **[Context-Aware Sensing](https://github.com/sathya8998/Multi-Modal-IMU-GNSS-Fusion-for-Indoor-Outdoor-Environment-Classification-with-XAI):** Fusing **IMU & GNSS** to decode environmental context from walking patterns.

---

## 🧠 Pillar II: Neuroengineering & BCI
*Developing zero-calibration systems for decoding high-dimensional brain states.*

* **[EEG-to-SEEG Translation](https://github.com/sathya8998/EEG-to-SEEG-Translation-with-TimeConformer-and-XAI):** Implements a **TimeConformer**-based encoder-decoder with Gradient Saliency XAI to reconstruct deep mesial temporal SEEG signals from non-invasive scalp EEG.
* **[Stroke Recovery Transformer](https://github.com/sathya8998/Multimodal-EEG-fNIRS-Fusion-Using-Transformers-for-Motor-Decoding-in-Stroke-Patients):** A Spatio-Temporal Transformer fusing **EEG & fNIRS** for subject-independent motor intent decoding.
* **[MEG Imagery Decoding](https://github.com/sathya8998/Cross-Subject-MEG-Imagery-Decoding-Using-Riemannian-Deep-Learning):** Mapping MEG waves into **Riemannian Tangent Space** for imagined object classification.
* **[Cognitive Load Network](https://github.com/sathya8998/EEG-fNIRS-Eye-Tracking-Cognitive-Load-Attention-Network):** Fusing **EEG, fNIRS, and Eye-Tracking** via attention-driven late fusion.
* **[Self-Supervised Brain MRI](https://github.com/sathya8998/Self-Supervised-3D-Multimodal-MRI-Classification):** Using **3D SimCLR** to identify brain alterations related to cognitive expertise.

---

## 🏥 Pillar III: Medical Imaging & Clinical AI
*Advanced Computer Vision for radiology and trustworthy diagnostic support.*

* **[Hypovolemic Instability Detection](https://github.com/sathya8998/Non-Invasive-Hypovolemic-Instability-Detection-with-PhysioFormer-and-LBNP):** Developed **PhysioFormer**, a multi-modal Spatio-Temporal Transformer, to predict multi-class LBNP severity from non-invasive physiological signals.
* **[Stroke CT Segmentation](https://github.com/sathya8998/Brain-Stroke-Detection-and-Segmentation-using-Multi-Task-ResNet-UNet):** Multi-task **ResNet-UNet** for simultaneous pathology classification and lesion localization.
* **[DermAI Safety Routing](https://github.com/sathya8998/DermAI-Domain-Aware-Soft-Routing-for-Skin-Classification):** Reliability-focused skin classification with **Safety Abstention** protocols.
* **[Knee OA Assessment](https://github.com/sathya8998/Knee-OA-Severity-Assessment-using-X-Ray-Thermal-Cross-Attention-Transformers):** Fusing **X-ray & Thermal** imagery using Cross-Attention Transformers for KL-grading.
* **[CT ↔ MRI Brain Tumor Translation](https://github.com/sathya8998/CycleGAN-CT-MRI-Brain-Tumor-Translation-OSATTA):** Trains two unpaired ResNet-9 CycleGAN generator–PatchGAN discriminator pairs for bidirectional CT↔MRI synthesis with **OSATTA** test-time domain adaptation and five-component loss (adversarial, cycle, identity, Sobel structural, VGG perceptual).

---

## 🧬 Pillar IV: Bioinformatics & Precision Medicine
*Applying Graph Neural Networks to transcriptomic and molecular interaction data.*

* **[Stroke Biomarker Discovery](https://github.com/sathya8998/Hybrid-Graph-Attention-Network-for-Ischemic-Stroke-Detection-and-Biomarker-Discovery):** Using **Graph Attention Networks (GAT)** to fuse gene expression with PPI networks for biomarker identification.
* **[Cancer Microenvironment Classification](https://github.com/sathya8998/Multi-Omics-Heterogeneous-GAT-XAI-Cancer-Microenvironment):** Integrates **scRNA-seq**, colorectal histology patches, and CCLE bulk cell-cycle data into a PyTorch Geometric heterogeneous graph. A dual-layer **HeteroGAT** (GATConv + SAGEConv) classifies single cells as malignant or benign, with gradient saliency XAI ranking molecular biomarkers across the tumour microenvironment.
* **[RNA Reactivity Prediction](https://github.com/sathya8998/RNA-Folding-TriFusion-Graph-LSTM-CNN-Stanford-Ribonanza):** Converts RNA sequences into biological graphs with **ViennaRNA BPP** structural edges, processed through three parallel branches — a TransformerConv graph network, packed BiLSTM, and Conv1d CNN — fused into a confidence-weighted regression head. Test-time augmentation averages forward and reverse predictions for per-nucleotide reactivity estimation.

---

## 🛠️ Technical Toolkit
* **Frameworks:** PyTorch (AMP/Lightning), TensorFlow, Scikit-Learn, XGBoost, Captum.
* **Signals:** EEG, fNIRS, MEG, HD-EMG, IMU, GNSS, Point Clouds (LiDAR), Ultrasound, CT, X-ray.
* **Mathematics:** Riemannian Geometry, Manifold Learning, Graph Theory, Signal Processing (PSD/Wavelets).

---

## 📫 Connect with Me
* **LinkedIn:** [Sathyanarayanan Dhorali](https://www.linkedin.com/in/sathyanarayanan-dhorali-74a4221b2/)
* **Email:** sathyanarayanan8998@gmail.com

---
*"Building AI that doesn't just predict, but explains."*
