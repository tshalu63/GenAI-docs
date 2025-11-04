# 10. Tools, Frameworks, and Libraries

**Key Libraries:**

- PyTorch / TensorFlow
- Hugging Face Transformers
- Diffusers (image generation)
- OpenAI API (text, image, code)

**Example:**
```python
from transformers import pipeline
generator = pipeline("text-generation", model="gpt2")
generator("Hello Generative AI", max_length=50)

---

## **11_evaluation_and_metrics.md**

```markdown
# 11. Evaluation and Metrics

### Text Generation
- Perplexity, BLEU, ROUGE, METEOR

### Image Generation
- FID, Inception Score, LPIPS

### Audio / Video
- MOS, SSIM, PESQ

**Best Practices**
- Combine human and automated evaluation
- Assess creativity, diversity, and realism
