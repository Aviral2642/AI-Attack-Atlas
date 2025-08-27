# AI Attack Mind Map – The Complete Guide to AI Security Threats

The **AI Attack Atlas** is the **most comprehensive mind map** of adversarial techniques, attack surfaces, and pivot paths across **modern AI systems**.

This version (`AI_Attack_Atlas_v2_expanded.opml`) is the **final expanded release**, incorporating:
- **Operator-style decision trees** (inspired by Active Directory attack maps)
- **State-driven branches**: *preconditions → enumeration → exploit → pivot → new goals*
- Coverage of **all AI paradigms**: LLMs, RAG, Agentic AI, RL/RLHF, multimodal, diffusion, federated learning, computer vision, speech, GNNs, and beyond
- **Cross-cutting threats**: prompt injection, jailbreaks, poisoning, model extraction, privacy attacks, adversarial examples, supply-chain compromise, GPU side-channels, economic DoS
- **Named classes & real-world issues**: *LeftoverLocals*, *GPU.zip*, *Morris II*, *Nightshade*, *DolphinAttack*, *Light Commands*
- **Operator playbooks** by foothold (e.g., no creds, API key, RAG KB write access, plugin publisher, neighbor GPU)

---

## 📂 Contents
- **`AI_Attack_Atlas_v2_expanded.opml`** → Import directly into [XMind](https://xmind.app/) or other OPML-compatible mind map tools.
- A Pdf version of the same mind map for your quick usage and reference.   
- **Future additions**: rendered PNG/PDF versions for quick previews, academic references, and visual exports  

---

## 🎯 Purpose
The **AI Attack Atlas** is designed to unify the fragmented landscape of AI security research into a **single operator-ready knowledge map**.  

It enables:
- **Red Teamers**: simulate realistic AI attack paths  
- **Defenders**: identify monitoring gaps and security controls  
- **Researchers**: explore overlooked vectors and attack surfaces  
- **Educators**: teach AI security through structured visuals  

---

## 🚀 Usage
1. Clone this repo:
   ```bash
   git clone https://github.com/aviral2642/AI-Attack-Atlas.git

2. Open AI_Attack_Atlas_v2_expanded.opml in XMind or any OPML-compatible mind map tool

3. Explore from precondition → to exploit → to pivot → to outcomes

🛡️ Disclaimer

This repository is for educational, research, and defensive security purposes only.
It does not contain or endorse weaponized exploit code.
The purpose is to improve AI threat modeling, strengthen defenses, and support the global AI security community.

🌐 Contributing

We welcome contributions:

Add new attack paths or missing paradigms

Link to new research papers, CVEs, or attack demonstrations

Suggest usability or visualization improvements

📣 Credits

Inspired by Active Directory attack maps made by esidate used in red-team operations 

Link - https://github.com/esidate/pentesting-active-directory

Built by synthesizing research from MITRE ATLAS, OWASP LLM Top 10, and academic/industry sources

Community-driven: meant to evolve as new AI threats emerge

⭐ Support

If you find this useful, please star the repo 🌟 and share with your peers.
Help us make AI security knowledge open, accessible, and actionable.
