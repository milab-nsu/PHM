<div align="center">
  
## Beyond Real Weights: Hypercomplex Representations for Stable Quantization

### **Accepted at WACV 2026**

Official repository for the paper  
**“Beyond Real Weights: Hypercomplex Representations for Stable Quantization”**

</div>

This paper proposes a progressive hypercomplex reparameterization framework for efficient and stable compression of multimodal large language models (MLLMs).

🔗 **Paper**: https://arxiv.org/abs/2512.08524  
🔗 **Code**: https://github.com/milab-nsu/PHM  

---

## 🚀 Key Contributions

- **Progressive PHM Reparameterization**  
  Smoothly replaces dense FFN layers with hypercomplex operators using residual interpolation.

- **Stability via Distillation & Reconstruction**  
  Combines dense-teacher → PHM-student knowledge distillation with operator-level reconstruction loss.

- **Selective Capacity Allocation**  
  Allocates higher hypercomplex capacity (B=3) to sensitive upper language layers for better performance.

- **Unified Multimodal Optimization**  
  Integrates PHM, LoRA-based PEFT, and KD into a single efficient training framework.

---

## Method Overview

<img width="1530" height="569" alt="image" src="https://github.com/user-attachments/assets/cb544b5f-934f-4816-97b0-353ca3dab7ac" />

---

## 📊 Experimental Results

<div align="center">
  
<img width="856" height="397" alt="image" src="https://github.com/user-attachments/assets/3e037acd-eb23-40cf-871b-4b7f24abdd6d" />

<img width="413" height="410" alt="image" src="https://github.com/user-attachments/assets/0764a3fc-6a22-4590-9ac0-32bff0a16f87" />

</div>

---

## 📚 Citation

If you find this work useful, please cite:

```bibtex
@article{ahad2025beyond,
  title={Beyond Real Weights: Hypercomplex Representations for Stable Quantization},
  author={Ahad, Jawad Ibn and Rahman, Maisha and Biswas, Amrijit and Kabir, Muhammad Rafsan and Krambroeckers, Robin and Momen, Sifat and Mohammed, Nabeel and Rahman, Shafin},
  journal={arXiv preprint arXiv:2512.08524},
  year={2025}
}

