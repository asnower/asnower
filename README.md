<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,100:333333&height=250&section=header&text=Dialogue%20Systems%20and%20NLP&fontSize=45&fontColor=ffffff&desc=PhD%20Candidate%20%7C%20Conversational%20AI%20%7C%20Knowledge-Grounded%20Dialogue&descSize=20&descAlignY=75" width="100%" />
</div>



<br/>

### 👨‍🔬 About Me

I am a Ph.D. researcher in **Conversational AI** at **Kobe University**.  
My work focuses on **dialogue systems**, especially **knowledge-grounded response generation** and the **DialFill framework** for reliably using retrieved information in open-domain dialogue. I am interested in building dialogue agents that can:

- faithfully use external knowledge instead of hallucinating,
- flexibly paraphrase rather than copy,
- and avoid generic, repetitive responses.

* 🎓 Ph.D. Candidate at **Kobe University**
* 🔍 Research topics: `Dialogue Systems`, `Knowledge-Grounded Dialogue`, `Retrieval-Augmented Generation`, `Dialogue Filling (DialFill)`, `Diffusion Language Models`, `Generative–Classification LMs`
* 🧪 Currently working on: `DialFill Framework (v1–v3)`, `DialFill-DM`, `JudgerToken-based repetition control`
* 📫 Contact: **xueqiang199305@gmail.com**

<br/>

---

### 🔬 Selected Projects & Publications

| **DialFill: Dialogue Filling for Knowledge-Grounded Dialogue** | **DialFill-DM: Diffusion Models for Controllable Dialogue** |
| :--- | :--- |
| <img src="./figs/dialfill_generation.png" width="100%"> | <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNzJqOThwODV4bnYzYnB4YnB4YnB4/giphy.gif" width="100%"> |
| • **IEEE Access, 2025** – reframes knowledge-grounded dialogue as a **Dialogue Filling** task instead of direct generation.<br>• Ensures that selected knowledge appears in the final response while keeping the wording natural.<br>• Evaluated on both structured and unstructured knowledge benchmarks (e.g., Wizard-of-Wikipedia, OpenDialKG).<br>• **Keywords:** Dialogue Filling, knowledge integration, retrieval-augmented generation.<br>• [![Paper](https://img.shields.io/badge/IEEE%20Access-Paper-blue)](YOUR_DIALFILL_PAPER_LINK) [![Code](https://img.shields.io/badge/GitHub-Code-black?logo=github)](YOUR_DIALFILL_CODE_LINK) | • **Diffusion-based Dialogue Filling** – replaces the autoregressive generator in DialFill with a **masked diffusion language model** for more controllable answer spans.<br>• Introduces a **length head** (to locate the answer region) and a **keyword head** (to control which entities are copied), improving robustness to noisy retrieval.<br>• Designed to integrate knowledge graphs and text passages in a compact, controllable way.<br>• **Keywords:** diffusion language models, controllable generation, knowledge-grounded dialogue.<br>• [![Paper](https://img.shields.io/badge/Paper-Preprint-blue)](YOUR_DIALFILL_DM_PAPER_LINK) [![Code](https://img.shields.io/badge/GitHub-Code-black?logo=github)](YOUR_DIALFILL_DM_CODE_LINK) |

<br/>

#### 🧵 More Research Highlights

- **Dialogue-Filling in Retrieval–Generation Systems**  
  Developed text-infilling based response control for retrieval–generation dialogue systems, ensuring that retrieved responses are actually used instead of ignored.

- **JudgerToken: Single-Token Repetition Control**  
  Proposed a **single-token generative–classification method** (JudgerToken) that uses the LM’s own logits to detect and suppress repetitive or low-quality responses without extra classifiers.

- **Knowledge Graph Memory for Dialogue**  
  Explored how to store and reuse knowledge-graph information inside dialogue models to improve consistency across turns.

<br/>

---

### 🛠️ Tech Stack

<div align="left">
  <a href="https://pytorch.org/">
    <img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white" />
  </a>
  <a href="https://www.tensorflow.org/">
    <img src="https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white" />
  </a>
  <a href="https://scikit-learn.org/">
    <img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  </a>
  <a href="https://www.python.org/">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  </a>
  <a href="https://www.latex-project.org/">
    <img src="https://img.shields.io/badge/LaTeX-47A141?style=for-the-badge&logo=LaTeX&logoColor=white" />
  </a>
</div>

<br/>

<div align="center">
  <a href="https://scholar.google.com/citations?user=kRPW4r0AAAAJ">
    <img src="https://img.shields.io/badge/Google%20Scholar-Follow%20My%20Research-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white" />
  </a>
</div>
