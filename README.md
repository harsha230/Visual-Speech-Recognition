#End-to-End Visual Speech Recognition  

An implementation of an end-to-end deep learning model for **Visual Speech Recognition** that directly maps lip movements in video to text sentences.  

It leverages **Spatio-Temporal Convolutional Neural Networks (STCNN)** for spatial and temporal feature extraction and **Bidirectional Gated Recurrent Units (Bi-GRUs)** for sequential modeling. Training is optimized with **Connectionist Temporal Classification (CTC) loss**, eliminating the need for manual frame-level alignments.  

This work demonstrates how deep learning enables machines to "read lips," opening new pathways for accessibility, security, and human-computer interaction.  

---

## ✨ Key Highlights
- **End-to-End Visual Speech Recognition** — directly converts lip movements from video into text.  
- **STCNN + Bi-GRUs** — captures both spatial and temporal dependencies.  
- **Alignment-Free Training** — powered by CTC loss.  
- **High Accuracy** — achieved **95.65% accuracy**, **Word Error Rate (WER): 8.33%**, and **Character Error Rate (CER): 2.17%**.  
- **Practical Applications**:  
  - Assistive technologies for hearing-impaired individuals  
  - Silent dictation in public spaces  
  - Speech recognition in noisy environments  
  - Biometric authentication & security systems  
  - Processing of silent video archives/movies  

## 🛠️ Tech Stack
- **Deep Learning**: TensorFlow, Keras  
- **Video Processing**: OpenCV, ImageIO  
- **Visualization**: Matplotlib, Streamlit  
- **Evaluation**: Jiwer, EditDistance  
- **Programming Language**: Python  

---


## 📈 Results

| Metric                     | Score      |
| -------------------------- | ---------- |
| Accuracy                   | **95.65%** |
| Word Error Rate (WER)      | **8.33%**  |
| Character Error Rate (CER) | **2.17%**  |

The system demonstrates robustness in varied scenarios, including:

* **Silent videos** (no audio)
* **Noisy environments** (background noise present)
* **Different lighting conditions**

---

## 🔮 Future Scope

* **Real-time Lip Reading** — enabling live transcription during meetings or events.
* **Multimodal Fusion** — combining visual cues with audio for improved robustness.
* **Scalability** — training on larger, diverse datasets covering multiple languages, accents, and speakers.
* **Deployment** — integration into assistive technologies, security systems, and video conferencing tools.
* **Generalization** — adapting to real-world unconstrained environments (different lighting, camera angles, and backgrounds).

---

## 📚 References

* Wand, M., Koutník, J., & Schmidhuber, J. (2016). *Lipreading with Long Short-Term Memory*, ICASSP.
* Chung, J. S., & Zisserman, A. (2017). *Lip Reading Sentences in the Wild*, CVPR.
* Petridis, S., Li, Z., & Pantic, M. (2017). *End-to-End Visual Speech Recognition with LSTMs*, ICASSP.
* Shillingford, B. et al. (2018). *Large-Scale Visual Speech Recognition*, arXiv.


