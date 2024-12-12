### Answers with Harvard References

---

**1. What is tokenization?**
Tokenization is the process of splitting text into smaller units, such as words, subwords, or characters, which can then be processed by machine learning models (Jurafsky & Martin, 2021).

---

**2. Why do we need to tokenize the input text?**
Tokenization is essential for converting unstructured text into a structured format that machine learning algorithms can process. It ensures proper interpretation of text by identifying meaningful units for analysis, facilitating tasks like sentiment analysis, translation, and text classification (Goldberg, 2017).

---

**3. How can we tokenize the input text?**
Input text can be tokenized using:
- **Whitespace Tokenization**: Splits text based on spaces.
- **Regex Tokenization**: Uses regular expressions for splitting text.
- **Subword Tokenization**: Breaks words into smaller subword units (e.g., Byte Pair Encoding).
- **Pre-trained Tokenizers**: Tools like Hugging Face's `BERTTokenizer` apply advanced methods for tokenization (Devlin et al., 2019).

---

**4. What is Natural Language Processing (NLP)? (Summarize in 20 words)**  
NLP enables machines to understand, interpret, and generate human language using computational techniques, enhancing interaction between humans and computers (Manning et al., 2008).

---

**5. Explain the idea of the sequence model in Deep Learning and how it relates to NLP.**  
Sequence models, like RNNs and Transformers, process sequential data by maintaining context through dependencies between elements, crucial for tasks like translation, speech recognition, and text generation. In NLP, sequence models handle text data by understanding dependencies between words, enabling accurate predictions and contextual analysis (Vaswani et al., 2017).

---

**6. Explain one-to-one, one-to-many, many-to-one, and many-to-many in sequence models.**  
- **One-to-One**: Maps a single input to a single output (e.g., image classification).  
- **One-to-Many**: Converts a single input into multiple outputs (e.g., image captioning).  
- **Many-to-One**: Maps multiple inputs to a single output (e.g., sentiment analysis).  
- **Many-to-Many**: Maps multiple inputs to multiple outputs (e.g., machine translation, video-to-text) (Goodfellow et al., 2016).

---

**7. Although the diffusion models outperform GAN and VAE for image generation, there are several challenges. Elaborate TWO challenges.**  
- **Computational Overhead**: Diffusion models require multiple iterative steps to refine noisy inputs into images, making them computationally expensive compared to GANs and VAEs (Ho et al., 2020).  
- **Mode Collapse Risk**: While less prone than GANs, diffusion models may still face difficulty generating diverse images due to limited training data (Dhariwal & Nichol, 2021).

---

**8. Briefly explain how conditional GAN works.**  
Conditional GANs (cGANs) condition the image generation process on additional information like class labels or text descriptions. The generator and discriminator are guided by this auxiliary input, enhancing control over output features (Mirza & Osindero, 2014).

---

**9. What is parallelization?**  
Parallelization refers to dividing computational tasks into smaller chunks that run simultaneously across multiple processors or cores, significantly improving speed and efficiency (LeCun et al., 2015).

---

**10. Briefly explain the idea of end-to-end in Deep Learning.**  
End-to-end deep learning involves training a model directly on raw inputs to produce desired outputs without intermediate feature engineering, enabling streamlined pipelines (Goodfellow et al., 2016).

---

**11. Elaborate on two difficulties in using GenAI algorithms to generate video data.**  
- **Temporal Consistency**: Ensuring smooth transitions between frames is challenging, requiring models to preserve spatial and temporal coherence (Wu et al., 2021).  
- **Computational Intensity**: Video generation demands high computational power due to the need to process spatial and temporal dimensions simultaneously, increasing training time and resources (Vondrick et al., 2016).

---

### **References**
- Devlin, J., Chang, M.W., Lee, K. & Toutanova, K., 2019. BERT: Pre-training of deep bidirectional transformers for language understanding. *arXiv preprint arXiv:1810.04805*.  
- Dhariwal, P. & Nichol, A., 2021. Diffusion models beat GANs on image synthesis. *NeurIPS 2021*.  
- Goldberg, Y., 2017. Neural network methods for natural language processing. *Morgan & Claypool Publishers*.  
- Goodfellow, I., Bengio, Y. & Courville, A., 2016. Deep learning. *MIT press*.  
- Ho, J., Jain, A. & Abbeel, P., 2020. Denoising diffusion probabilistic models. *arXiv preprint arXiv:2006.11239*.  
- Jurafsky, D. & Martin, J.H., 2021. Speech and language processing. 3rd ed. *Pearson*.  
- LeCun, Y., Bengio, Y. & Hinton, G., 2015. Deep learning. *Nature*, 521(7553), pp.436-444.  
- Manning, C.D., Raghavan, P. & Schütze, H., 2008. Introduction to information retrieval. *Cambridge University Press*.  
- Mirza, M. & Osindero, S., 2014. Conditional generative adversarial nets. *arXiv preprint arXiv:1411.1784*.  
- Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A.N., Kaiser, Ł. & Polosukhin, I., 2017. Attention is all you need. *Advances in Neural Information Processing Systems*.  
- Vondrick, C., Pirsiavash, H. & Torralba, A., 2016. Generating videos with scene dynamics. *NeurIPS*.  
- Wu, J., Zhang, Y., Wang, W., Lin, Z. & Shen, J., 2021. Temporal modeling in video understanding: A comprehensive survey. *arXiv preprint arXiv:2109.03012*.
