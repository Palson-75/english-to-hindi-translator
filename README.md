# English to Hindi Neural Machine Translation using Phi-mini

This project focuses on fine-tuning **Microsoft’s Phi-mini large language model** for **English to Hindi translation** using **Parameter-Efficient Fine-Tuning (PEFT)** with **LoRA-based quantization**. The training and experimentation were performed on **Google Colab**, enabling efficient model training under limited GPU resources.

---

##  Overview
Neural Machine Translation (NMT) is a core NLP task. In this project, a pre-trained **Phi-mini LLM** is adapted for English → Hindi translation by applying **LoRA (Low-Rank Adaptation)**, significantly reducing the number of trainable parameters while maintaining translation quality.

---

##  Key Features
- Fine-tuned **Microsoft Phi-mini** for English → Hindi translation
- Applied **PEFT with LoRA-based quantization** for memory-efficient training
- Reduced GPU memory usage while preserving model performance
- End-to-end training and inference pipeline implemented
- Experiments conducted on **Google Colab**

---

## Tech Stack
- **Programming Language:** Python  
- **Framework:** TensorFlow  
- **Libraries:**  
  - Hugging Face Transformers  
  - PEFT (LoRA)  
- **Platform:** Google Colab  

---

## Workflow
1. Load and preprocess parallel English–Hindi dataset
2. Tokenize text using Hugging Face tokenizers
3. Configure PEFT with LoRA and quantization
4. Fine-tune Phi-mini on translation task
5. Evaluate model performance using BLEU score
6. Run inference on unseen sentences

---

##  Evaluation
- Used standard machine translation metrics such as **BLEU score**
- Compared fine-tuned model outputs with baseline translations

---

##  Future Improvements
- Train on larger and more diverse parallel corpora
- Experiment with different LoRA ranks and quantization levels
- Deploy the model as an API for real-time translation
- Add beam search decoding for improved translation quality

---

##  References
- Microsoft Phi Models
- Hugging Face Transformers Documentation
- PEFT & LoRA Research Papers

---

##  Author
**Palson Raj Garnipudi**  
Aspiring AI / Deep Learning Engineer  


# english-to-hindi-translator
