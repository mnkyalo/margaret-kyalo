# Hi, I'm Margaret Kyalo-Omamo 👋
 
### 🧪 Scientific AI Evaluation Designer · 🌍 Aquatic Ecologist & Molecular Biologist
 
I design **research-grade evaluation tasks** that test whether AI agents can do real scientific computing: calibrate instruments, screen contaminated data, fit physical models and defend a quantitative answer. Each task is built from my own field and lab training in the lakes of the East African Rift. It is packaged with **Docker and the [Harbor](https://www.harborframework.com/docs/tasks) framework** and graded by a verifier with **measured tolerances**, proven against **plausible wrong answers**.
 
African aquatic ecosystems are underrepresented in science and even more so in AI benchmarks. I build tasks from the systems I know first hand, so models are tested on the science as it is actually practised there.
 
---
 
## 🔬 Featured: AI Evaluation Tasks
 
| Repository | Setting | What the agent must get right | Evaluation engineering |
| :--- | :--- | :--- | :--- |
| **[Naivasha Pesticides](https://github.com/mnkyalo/ai-eval-task-naivasha-pesticides)** | Lake Naivasha basin, Kenya · environmental chemistry | Recover dissolved concentrations of 19 organochlorine pesticides from two passive-sampler types: sampler memory under a falling concentration, in-situ calibration, uptake bound to dissolved organic matter | Seeded generator rebuilds data and answer key byte for byte · 57 graded values · honest methods 57/57, textbook answer 23/57 |
| **[Congo Peat Pollen](https://github.com/mnkyalo/ai-eval-task-congo-peat-pollen)** | Cuvette Centrale, Congo Basin · palaeoecology | Radiocarbon chronology and pollen influx: hemispheric calibration curve, contaminated dates, spike-corrected influx, closed-sum artefacts | 82 checks · verifier re-derives the answer from sealed data · 7 wrong answers each fail in their own section |
 
Each task repo includes a **validation harness**. It runs the reference solution, honest alternative methods and plausible wrong answers through the real verifier, and **GitHub Actions CI** re-runs it on every push. Each repo also includes a candid design review of the task's weak points.
 
### How I design a task
1. **Start from real computational work**, so the difficulty comes from the science, not from withheld information.
2. **Build the data from a seeded generator** with literature-anchored parameters, so the ground truth is exact and reproducible.
3. **Measure the tolerances.** Each band sits between the spread of honest implementations and the smallest error it must catch.
4. **Prove the grader works.** Every plausible wrong answer is built as a real submission and must fail for the reason it models.
5. **Harden the verifier.** It runs in a separate container, uses sealed ground truth and writes a binary reward on every code path.
---
 
## 🛠️ Core Technical Expertise
 
* **Scientific AI Evaluation & Task Design:** research-grade benchmark authoring, grader and rubric design, tolerance calibration, adversarial wrong-answer validation, verifier hardening.
* **Scientific Computing (Python):** NumPy, SciPy, pandas; non-linear least squares, inverse problems, calibration and uncertainty, time-series deconvolution, reproducible simulation.
* **Evaluation Infrastructure:** Docker, Harbor, pytest, GitHub Actions CI, Git.
* **LLM Evaluation & Alignment:** RLHF pairwise preference ranking, hallucination detection, red teaming, fact-checking benchmarks.
* **AI Data Annotation & Curation:** Label Studio, CVAT, Labelbox, COCO 1.0 JSON, YOLOv8 PyTorch formats; polygon instance segmentation, thermal-domain perception, custom NER taxonomies.
* **Domain Science:** hydrobiology and saline-lake ecology, palaeoecology and sediment cores (radiocarbon, diatoms), sedimentary ancient DNA (extraction, PCR, cloning, clean-room contamination control, phylogenetics), organochlorine contamination, primary productivity (chlorophyll a, oxygen methods).
* **Design Thinking & Human-Centred Design:** Hasso Plattner Institut certificates.
---
 
## 🎓 Research Background
 
* **MSc Hydrobiology**, University of Nairobi. Thesis on lesser flamingo food resources in the alkaline-saline lakes of the eastern Rift Valley.
* **PhD (Cand.) research**, University of Potsdam, Germany (2012–2018). Sedimentary ancient DNA; coursework completed; fellowship recipient.
* **First author**, [Kyalo-Omamo et al. 2023, *Freshwater Biology* 68:1894–1916](https://doi.org/10.1111/fwb.14093). sedaDNA of rotifers and 200 years of climate change in two Kenyan crater lakes.
* **Co-author**, [Bettinetti et al. 2011, *AMBIO* 40:341–350](https://doi.org/10.1007/s13280-011-0142-8). DDT contamination in the sediments of Lakes Natron and Bogoria.
---
 
## 📌 Annotation & LLM Evaluation Case Studies
 
| Repository | Domain | Tools / Frameworks | Focus Area |
| :--- | :--- | :--- | :--- |
| **[Automated PCR Gel Instance Segmentation](https://github.com/mnkyalo/Automated_PCR_Agarose_Gel_Instance_Segmentation_AI_Model_Training_with_CVAT_YOLOv8)** | Molecular Biology | CVAT, YOLOv8-seg | DNA band & ladder polygon instance segmentation. |
| **[RLHF Hydrobiology Benchmark](https://github.com/mnkyalo/RLHF-Fact-Checking-Benchmark-Ecosystem-Engineering-in-Hydrobiology)** | LLM Alignment | Label Studio | STEM hallucination detection, error classification & pairwise ranking. |
| **[ADAS Thermal Perception & VRU Segmentation](https://github.com/mnkyalo/ADAS-Thermal-Nighttime-Perception-VRU-Segmentation)** | Autonomous Driving | Extended COCO 1.0 | Zero-visibility thermal VRU detection with custom pose/proximity attributes. |
| **[Mobile E-Commerce UI Micro-Element Segmentation](https://github.com/mnkyalo/Mobile-E-Commerce-UI-Micro-Element-Segmentation)** | Visual UX Audit | Label Studio Polygons | 34° perspective distortion compensation & UI interaction taxonomies. |
| **[B2B Market Intelligence Reports NER](https://github.com/mnkyalo/B2B-Market-Intelligence-Reports-NER)** | NLP / Market Analysis | Label Studio, JSON | Multi-class token classification for macroeconomic & investment reports. |
 
---
 
## 📬 Connect With Me
 
* **Email:** [mnkyalo22@gmail.com](mailto:mnkyalo22@gmail.com)
* **Location:** Kenya
 
