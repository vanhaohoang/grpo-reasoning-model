# 🚀 GRPO-Powered AI Reasoning Engine

Unlock the power of **AI reasoning** with GRPO and LoRA fine-tuning! This project builds a robust reasoning model inspired by **DeepSeek-R1**, leveraging **Unsloth** for ultra-fast training and inference. 🧠💡

---

## ⚡ Quick Setup

Get started in minutes! Ensure you have **Python 3.11+**, then install the dependencies:

```bash
pip install unsloth vllm
pip install --upgrade pillow
pip install git+https://github.com/huggingface/trl.git@e95f9fb74a3c3647b86f251b7e230ec51c64b72b
```

---

## 🔥 Features

✅ **Ultra-fast inference** with Unsloth 🚀  
✅ **LoRA fine-tuning** for efficient adaptation 🎯  
✅ **Structured reasoning** for high-quality AI responses 📜  
✅ **Multi-layer reward functions** to optimize training 🎓  
✅ **GRPO training** for better reinforcement learning ⚙️  

---

## 🛠 Training & Fine-Tuning

Easily train and fine-tune the model with **GRPO and LoRA**. We provide a structured reward system to enhance output correctness, format consistency, and numerical reasoning. 🏋️‍♂️💡

```python
trainer.train()
```

---

## ⚡ Instant Inference

Ask your AI a question and get structured responses:

```python
query = "Which is bigger, 9.11 or 9.9?"
output = model.fast_generate([text], sampling_params=SamplingParams(temperature=0.8, top_p=0.95, max_tokens=1024))[0].outputs[0].text
print(output)
```

---

## 🤝 Contribute & Improve

We welcome contributions! Fork the repo, improve the code, and submit a pull request. Let’s build the future of AI reasoning together! 🚀✨

