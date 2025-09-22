# 🛡️ Backdoor Defense Papers Collection

> 📚 **A comprehensive collection of research papers on backdoor defenses in machine learning.**  
> 🎓 **Maintained by**: Dr. [Minwei Wen] | [Chongqing University of Posts and Telecommunications] | [2058477814@qq.com]

## 📖 About This Repository

This repository serves as a curated collection of academic papers focusing on **defense mechanisms** in machine learning. Our goal is to provide researchers, practitioners, and students with a comprehensive overview of the current state-of-the-art in this critical security domain.


### 🎯 **Repository Purpose:**
- 🏆 **Quality Focus**: Emphasis on high-impact venues. [CCF-Rankings](https://www.ccf.org.cn/en/About_CCF/Media_Center/) now marked with different colors(![arXiv](https://img.shields.io/badge/CCF_A-dc3545) ![Static Badge](https://img.shields.io/badge/CCF_B-ffc107) ![Static Badge](https://img.shields.io/badge/CCF_C-28a745) ![Static Badge](https://img.shields.io/badge/CCF_None-6c757d))
- 🔄 **Regular Updates**: Continuously updated with latest research developments
- 🌐 **Easy Access**: Direct links to papers, code repositories, and supplementary materials

### 📊 **Each paper includes the following evaluation metrics (out of 5 stars):**
- **💡 Motivation**: How well-motivated and significant is the research problem? ⭐⭐⭐⭐⭐ (5/5)
- **🔧 Method**: How novel and technically sound is the proposed approach? ⭐⭐⭐⭐⭐ (5/5)

<h2 id="awesome-papers"> 👑 Awesome Papers List </h2>

<h3 id="attacks"> 2023 </h3>

* **[2023.08.23]** **[BaDExpert: Extracting Backdoor Functionality for Accurate Backdoor Input Detection](https://openreview.net/forum?id=s56xikpD92)** ![Static Badge](https://img.shields.io/badge/ICLR'24-6c757d) [![GitHub stars](https://img.shields.io/github/stars/vtu81/backdoor-toolbox?style=social)]([https://github.com/yunqing-me/AttackVLM](https://github.com/vtu81/backdoor-toolbox)) 
  * Yunqing Zhao, Tianyu Pang, Chao Du, Xiao Yang, Chongxuan Li, Ngai-Man Cheung, Min Lin
  * **📝 Summary**: A novel approach that extracts backdoor functionality from infected models to enable accurate detection of backdoor inputs without requiring clean reference data.
  * **💡 Motivation**: ⭐⭐⭐⭐⭐ (5/5) - Addresses the critical challenge of backdoor detection in practical scenarios where clean data is unavailable
  * **🔧 Method**: ⭐⭐⭐⭐⭐ (5/5) - Innovative backdoor functionality extraction technique with strong theoretical foundation and empirical validation

<h3 id="attacks"> 2025 </h3>

* **[2025.04.11]** **[Adversarial-Inspired Backdoor Defense via Bridging Backdoor and Adversarial Attacks](https://ojs.aaai.org/index.php/AAAI/article/view/33030)** ![Static Badge](https://img.shields.io/badge/AAAI'25-6c757d)![arXiv](https://img.shields.io/badge/CCF_A-dc3545)
  * Jia-Li Yin, Weijian Wang, Lyhwa, Wei Lin, Ximeng Liu
  * **📝 Summary**: Leveraging the intrinsic connection between adversarial attacks and backdoor attacks to effectively isolate poisoned samples and weaken the association between backdoor triggers and target labels.
  * **💡 Motivation**: ⭐⭐⭐⭐⭐ (5/5) - 1) the sample is harder to be turned into an adversarial examples when the trigger is presented; 2) the adversarial examples generated from backdoor samples are highly likely to be predicted as its true labels.
  * **🔧 Method**: ⭐⭐⭐⭐ (4/5) - Designed a clever top-q strategy to select poisoned samples.

* **[2025.01.23]** **[Activation Gradient based Poisoned Sample Detection Against Backdoor Attacks](https://openreview.net/forum?id=VNMJfBBUd5)** ![Static Badge](https://img.shields.io/badge/ICLR'25-6c757d)
  * Danni Yuan, Shaokui Wei, Mingda Zhang, Li Liu, Baoyuan Wu
  * **📝 Summary**: By analyzing the distribution differences of activation gradients in the model, it effectively identifies target classes and distinguishes between clean and poisoned samples.
  * **💡 Motivation**: ⭐⭐⭐⭐⭐ (4/5) - Backdoored models tend to map significantly different poisoned samples and clean samples to similar activation regions.
  * **🔧 Method**: ⭐⭐⭐⭐ (4/5) - Designed a novel class-level and sample-level selection method.
