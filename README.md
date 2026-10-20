![Logo IntuYT](https://intu.yt/assets/intuyt.svg)

# The `intuyt` Model Family by LLM-MX

The **intuyt** family represents a sovereign, highly efficient suite of Large Language Models developed under the **LLM-MX** initiative. Engineered to deeply understand Mexican Spanish and optimized for GreenAGI principles, the models span from ultra-efficient edge computing prototypes to robust reasoning engines.

---

## 🚀 Model Lineup

### 1. intuyt:nano (1.7B VLM) - *Available Now*
* **Base Architecture:** Qwen3 (1.7B)
* **Tuning Method:** Extensive Fine-Tuning
* **Quantization:** Q4_K_M (1.1GB)
* **Role:** Edge computing optimized. Ideal for low-latency, offline local inference on resource-constrained devices (tablets, local gateways) requiring Vision-Language (VLM) capabilities and native Mexican Spanish.

### 2. intuyt:micro (4B) - *Prototyping Phase*
* **Base Architecture:** Qwen3:4b-instruct
* **Tuning Method:** Heavy System Prompting (Giga-Prompting)
* **Role:** Advanced logic and agentic workflow orchestration.
* **Technical Justification for Giga-Prompting:** 
While traditional fine-tuning permanently updates model weights, `intuyt:micro` is currently deployed using **Heavy System Prompting (Giga-Prompting)**. In modern, highly-aligned instruct architectures like Qwen3, comprehensive system prompting is a scientifically valid and compute-efficient method for model tuning and rapid prototyping. 
By front-loading strict behavioral constraints, topological schemas, and few-shot reasoning examples into an expanded context window, we effectively perform *activation steering*—guiding the model's latent representations toward the desired outputs without the risk of catastrophic forgetting. This approach allows for rapid, cost-effective iteration of complex agent behaviors (e.g., formatting for n8n or OpenClaw pipelines). Furthermore, it acts as a synthetic data engine, generating the exact, highly-curated conversational datasets required for its upcoming explicit fine-tuning phase, perfectly aligning with GreenAGI principles by saving massive amounts of preliminary compute.

### 3. intuyt:macro (30B) - *Upcoming*
* **Base Architecture:** Qwen3:30b-a3b-instruct (Mixture of Experts)
* **Role:** The flagship reasoning engine of the LLM-MX initiative. Designed for enterprise-grade deployments, massive transdisciplinary data analysis, and serving as the central orchestrator for complex GreenAGI multi-agent topologies.

---

## 🤝 Ecosystem & Acknowledgments

The development of the **intuyt** family is driven by a robust network of academic, research, and industry partners:

### Core Research & Applied AI
* [**intu.yt**](https://intu.yt): The main hub for the LLM-MX initiative and tailored Mexican AI models.
* [**TRAI-L**](https://trai-l.com): The Transdisciplinary Research for Augmented Innovation Laboratory, leading the theoretical frameworks for GreenAGI and modular neurosymbolic AI.
* [**ArtInt.Tech**](https://artint.tech): Bridging the gap between cutting-edge local LLM research and enterprise agentic workflow implementations.

### Academic & Institutional Partners
* [**NLP Lab @ CIC-IPN**](https://www.cic.ipn.mx/views/investigation/lab_pln.php): The Natural Language Processing Laboratory at the Centro de Investigación en Computación (IPN), driving foundational research in computational linguistics and indigenous language preservation.
* [**IPICYT**](https://www.ipicyt.edu.mx/): Instituto Potosino de Investigación Científica y Tecnológica, fostering advanced scientific research and technological development in Mexico.
* [**Universidad de Sonora (Unison) & Summa IT**](https://www.unison.mx/): Key collaborators in the expansion of AI capabilities, technological integration, and applied research across academic and enterprise sectors.

### Hardware & Infrastructure
* [**AMD**](https://www.amd.com): Providing the high-performance ROCm compute power (Instinct accelerators) required for local deployment and fine-tuning.
* [**Dell Technologies**](https://www.dell.com): Supplying the enterprise-grade server architecture that supports our intensive local AI deployments and research pipelines.
