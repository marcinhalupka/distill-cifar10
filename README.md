# 🧠 Model Distillation on CIFAR-10: From ResNet to a Tiny CNN

This repo contains the **hands-on complement** to my blog post:

➡️ [What the heck is model distillation – and why should you care?](https://medium.com/@marcinhaupka/what-the-heck-is-model-distillation-and-why-should-you-care-058d9f08d460)

We take the core ideas from that article and bring them to life by:
- Training a **ResNet18 teacher** from scratch on CIFAR-10
- Distilling it into a **tiny custom CNN** with ~98% fewer parameters
- Comparing accuracy, size, and capabilities of both models
- Visualizing predictions and running comparisons

---

## 📚 What You'll Find Here

- `distill_cifar10.ipynb` — Colab-ready notebook to try the full pipeline
- 📸 Grids of predicted images from both models
- 📦 Model size and parameter comparisons
- 🔬 Cleanly written PyTorch code for distillation training

---

## 🚀 Quick Preview

| Model       | Accuracy | Parameters | File Size |
|-------------|----------|------------|-----------|
| Teacher     | ~75%     | 11.2M      | 42.7 MB   |
| Student     | ~66%     | 211K       | 0.81 MB   |

✨ The student model retains ~87% of the performance with only 2% of the size!

---

## 📎 License

MIT — use it freely and remix for your own projects.

---

> Made with ☕ and curiosity by [@marcinhaupka](https://medium.com/@marcinhaupka)
