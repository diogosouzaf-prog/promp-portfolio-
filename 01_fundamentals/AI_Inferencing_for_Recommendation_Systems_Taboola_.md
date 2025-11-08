# AI Inferencing for Recommendation Systems — Taboola

**Author:** Diogo Fernandes de Souza  
**Platform:** Coursera – Intel® AI Fundamentals Series  
**Module:** AI Inferencing for Recommendation Systems (Taboola)  
**Version:** v2 (Corrected Answers and Explanations)

---

## 1. What is Intel® MKL-DNN now known as?
✅ **Intel® oneAPI Deep Neural Network Library (Intel® oneDNN)**  
*Explanation:* Intel rebranded MKL-DNN as oneDNN, providing deep neural network performance optimizations for Intel architectures.

---

## 2. What class of machine learning uses data to predict a user’s preference for (or rating of) an item?
✅ **Recommendation**  
*Explanation:* Recommendation systems are designed to predict user preferences or ratings based on past interactions or data.

---

## 3. Which of the following is a use case for a recommendation engine (or system)?
✅ **Books and other products (e.g. Amazon)**  
✅ **Music (e.g. Pandora)**  
✅ **Movies (e.g. Netflix)**  
✅ **Restaurants (e.g. Yelp)**  
✅ **Jobs (e.g. LinkedIn)**  
*Explanation:* All these platforms use recommendation systems to personalize user experiences.

---

## 4. According to this course, what are publishers, marketers, and advertising agencies using more and more?
✅ **AI applications via software-as-a-service (SaaS) cloud platforms.**  
*Explanation:* SaaS-based AI tools allow scalable and cost-efficient marketing analytics.

---

## 5. Taboola’s recommendation engine works in two parts. What are they?
✅ **Machine learning using deep neural networks to infer user preferences and then processing/delivery of real-time content recommendations.**  
*Explanation:* Taboola leverages deep learning to personalize and deliver real-time recommendations.

---

## 6. Taboola’s algorithms must work in real time to infer the right content recommendations within _____.
✅ **100 milliseconds.**  
*Explanation:* Real-time AI systems typically operate under 100ms latency to ensure instant responses.

---

## 7. What does the company require as it continues to expand and improve its recommendation engine?
✅ **Steady increases in the power and capacity of its computing infrastructure.**  
*Explanation:* More users and data demand higher processing capacity and power.

---

## 8. What was Taboola’s main concern when evaluating moving from CPUs to GPUs for AI inferencing?
✅ **The overhead of moving from CPU to GPU memory.**  
*Explanation:* Transferring data between CPU and GPU memory adds latency and reduces efficiency.

---

## 9. According to this course, what does “TFS” mean?
✅ **TensorFlow-Serving, an open-source deployment service for running machine learning models in production environments.**  
*Explanation:* TFS enables efficient serving of trained TensorFlow models in real-time inference pipelines.

---

## 10. What was Taboola’s AI hardware based on?
✅ **Intel® Xeon® Scalable 8180 processors optimized with Intel® oneDNN and the Intel® VTune™ Amplifier.**  
*Explanation:* These tools provided the performance optimization necessary for deep learning inference workloads.

---

## 11. What was the largest factor in powering Taboola’s deep learning algorithms?
✅ **One of the largest datasets of content consumption behavior across the open web.**  
*Explanation:* Large datasets are essential for training and improving deep learning recommendation accuracy.

---

## 12. “Matrix to matrix multiplication” is otherwise known as what?
✅ **SGEMM**  
*Explanation:* SGEMM (Single-Precision General Matrix Multiply) is a core operation in optimized neural network computations.

---

## 13. Which statement is true?
✅ **Intel® oneDNN (formerly known as Intel® MKL-DNN) provides primitives for neural network processing that are highly optimized for performance on the latest Intel® microarchitecture.**

---

## 14. What did the team use to optimize performance on TensorFlow?
✅ **Intel® oneAPI Deep Neural Network Library (Intel® oneDNN)**  
*Explanation:* Intel® oneDNN optimizes deep learning frameworks like TensorFlow for Intel CPUs.

---

## 15. To increase performance in this case study, what did Intel engineers pin TensorFlow-Serving (TFS) threads to?
✅ **A corresponding processor socket.**  
*Explanation:* Pinning threads to processor sockets improves memory locality and performance consistency.

---

## 16. What did Intel engineers use to identify performance bottlenecks?
✅ **Intel® VTune™ Amplifier.**  
*Explanation:* VTune™ analyzes performance hotspots in real time to optimize inference efficiency.

---

## 17. What is a “tensor”?
✅ **An n-dimensional array of numbers.**  
*Explanation:* Tensors are mathematical representations used by deep learning models to process data in multiple dimensions.

---

## 18. An example of a tensor broadcast operation is ______.
✅ **Executing an instruction many times across a large number of data points.**  
*Explanation:* Broadcasting applies an operation to multiple data elements simultaneously.

---

## 19. What process best fits the single instruction multiple data (SIMD) capabilities in Intel® Xeon® processors using Intel® AVX?
✅ **Tensor broadcasting operations.**  
*Explanation:* SIMD and AVX execute the same operation across multiple data points efficiently.

---

**End of File — AI Inferencing for Recommendation Systems (Taboola)**  
*Intel® AI Fundamentals Series*  
