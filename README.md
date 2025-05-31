# 🧠 "Attention Is All You Need" – Transformer Model

Welcome! 👋 This project is a from-scratch implementation of the **Transformer** architecture from the groundbreaking research paper [“Attention Is All You Need”](https://arxiv.org/abs/1706.03762) by Vaswani et al. (2017). This model is the foundation for modern NLP architectures like BERT, GPT, and many more.

The goal of this repo is to help you understand how Transformers work by building each piece step-by-step with clean and readable code.

---

## ✨ What’s Inside

- Encoder and Decoder modules (just like in the original paper)
- Multi-head self-attention
- Positional encoding (so the model knows the word order)
- Scaled dot-product attention
- Masking for padding and future tokens
- Training pipeline with sample translation task (English → German)

---

## 📖 Quick Overview of the Paper

The Transformer model is a neural network based entirely on **attention mechanisms**, without using any RNNs or CNNs. It works by looking at all the words in a sentence at once and figuring out which ones matter most when generating the next word.

Some key ideas:
- Use **self-attention** to capture relationships between words
- Encode the order of words with **positional encodings**
- Stack layers of encoders and decoders
- Train it end-to-end with lots of data

---

## 🛠️ Getting Started

1. **Clone the repository**

```bash
git clone https://github.com/externalPointerVariable/AttentionIsAllYouNeed.git
cd AttentionIsAllYouNeed
```
