# 11. Evaluation and Metrics for Generative AI

Evaluating generative AI is **different from traditional AI**, as we need to assess **creativity, realism, diversity, and alignment with prompts**.

---

## 1. Text Generation Metrics

- **Perplexity:** Measures how well a model predicts the next word.
- **BLEU:** Compares generated text with reference text (precision-based).
- **ROUGE:** Focuses on recall (important for summarization).
- **METEOR:** Considers synonyms and semantic similarity.

---

## 2. Image Generation Metrics

- **FID (Fréchet Inception Distance):** Measures similarity between generated and real images; lower is better.
- **Inception Score (IS):** Evaluates both quality and diversity.
- **LPIPS (Learned Perceptual Image Patch Similarity):** Measures perceptual similarity between images.

**Qualitative evaluation:**  
- Visual inspection is crucial; AI may produce realistic images that metrics alone cannot fully capture.

---

## 3. Audio/Video Metrics

- **MOS (Mean Opinion Score):** Human evaluators rate quality (1–5 scale).
- **PESQ (Perceptual Evaluation of Speech Quality):** Automatic speech quality assessment.
- **SSIM (Structural Similarity Index):** Video or image structural similarity.

---

## 4. Best Practices

- Combine **automatic metrics** with **human evaluation**.
- Evaluate **creativity, alignment, and diversity**, not just accuracy.
- Compare outputs with **multiple reference examples** for better assessment.
- For multimodal AI, ensure **consistency across modalities** (e.g., text-to-image matching the prompt).
