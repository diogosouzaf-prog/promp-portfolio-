# AI in HPC: High Energy Physics at CERN
Intel® AI Essentials — Course 2: The Intel® AI Value

## ✅ Correct Answers and Explanation

### 1. How did workflow convergence use AI in the CERN case study?
**Answer:** Improve workflow of a traditional HPC job.

### 2. According to this course, how does application convergence use AI in the HPC segment?
**Answer:** Replace a traditional mod/sim workload.

### 3. What removed the need for humans to assess results and allowed simulations to run as needed?
**Answer:** Workflow convergence.

### 4. What does CERN compare in order to generate new particles?
**Answer:** Theoretical models to data.

### 5. What did CERN replace Monte Carlo with to achieve faster simulations?
**Answer:** A deep neural network (DNN) that directly generates data detector outputs.

### 6. Previous to switching their model, what software library did CERN use to simulate particle showers?
**Answer:** Geant4.

### 7. After switching their model, what did CERN use to reproduce full particle showers in one pass?
**Answer:** 3D Convolutional GANs (Generative Adversarial Networks).

### 8. What best describes a generative adversarial network (GAN) AI model?
**Answer:** An AI model with two networks: a generative network and a discriminator network.

### 9. What did the generator network do in the CERN case study?
**Answer:** Took in random data (or noise) and returned an image known as fake data.

### 10. What did the discriminator network do in the CERN case study?
**Answer:** Compared real data with fake data to determine and return any loss between them.

### 11. During CERN’s use of a GAN, any determined loss output between real and fake data was fed back to what?
**Answer:** The discriminator network **and** the generator network. ✅ *Correction applied.*

### 12. In CERN’s use of a GAN, when did the loss feedback to the discriminator and generator network stop?
**Answer:** When the discriminator network could no longer distinguish between real data and fake data.

### 13. What software was used to train CERN’s 3D AI model on Intel® Xeon® clusters?
**Answer:** Keras, TensorFlow, and Horovod.

### 14. What was mainly responsible for CERN’s 3D-GAN model realizing a 4.9x improvement in throughput?
**Answer:** Quantizing the floating point 32 (FP32) AI model to INT8 for inference purposes and optimizing it on Intel® Xeon® processors.

### 15. What was mainly responsible for CERN’s AI model realizing a 20,000x improvement over the classical Monte Carlo method?
**Answer:** Switching to a 3D GAN model and increasing the number of streams from one to four.

### 16. What was responsible for CERN achieving a 98,000x increase in inferencing throughput speed?
**Answer:** A combination of switching from a classical AI model to a 3D GAN model, upgrading to 3rd Gen Intel® Xeon® 8380 processors, quantizing, and performing software optimizations.

---

## 🧩 Summary of Learning
CERN successfully integrated **AI and HPC (High-Performance Computing)** to accelerate particle physics simulations. By replacing the traditional Monte Carlo method (Geant4) with **3D GANs**, the institution achieved **exponential performance gains** in both speed and efficiency.  
The use of **Intel® Xeon® Scalable Processors**, **TensorFlow**, **Keras**, and **Horovod** enabled large-scale distributed training and inference optimization.  
This marked a new milestone in scientific computing, reducing simulation time from **weeks to hours** while maintaining high data accuracy.

---
*Created by Diogo Fernandes de Souza — Intel AI Essentials Portfolio (GitHub Version)*
