# Equity Research & Industry Notes

A curated collection of my undergraduate equity research and industry overview work, with a focus on AI infrastructure and semiconductor-related themes.

---

## 1. AI ASIC Industry Overview

**Language:** Chinese  
**Format:** Slide deck (PPTX/PDF)  
**Role:** Team member (research, structuring, and writing)  
**Topic:** AI ASIC supply chain, growth drivers, risks, and investment ideas

### 1.1 Scope & Objectives

This piece provides a structured overview of the AI ASIC industry and its role within the broader AI infrastructure stack. It aims to:

- Map out the **value chain** from IP & EDA, IC design, foundry, advanced packaging, to downstream applications (data centers, networking, consumer, automotive).
- Compare **ASIC vs GPU** in terms of performance, cost, flexibility, and typical use cases.
- Analyze how hyperscale cloud providers (CSPs) are driving ASIC adoption through self-developed accelerators.
- Identify potential **investment candidates** and key factors to monitor going forward.

### 1.2 Industry Value Chain

The deck outlines the AI ASIC supply chain as follows:

- **IP & EDA:** ARM, Synopsys, Cadence – providing fundamental IP blocks and design tools. :contentReference[oaicite:2]{index=2}  
- **IC Design & Design Services:**  
  - Taiwan-based players such as Alchip (世芯-KY), Global Unichip (創意), Faraday (智原)  
  - Global players such as Broadcom (AVGO), Marvell (MRVL), MediaTek, etc.
- **Foundry:**  
  - Pure-play: TSMC, UMC, GlobalFoundries, SMIC  
  - IDM + Foundry: Intel, Samsung
- **Packaging & Testing:** ASE, PTI, Amkor, KYEC, as well as TSMC’s CoWoS and advanced packaging lines.
- **Downstream Applications:** Hyperscale data centers (Google, Amazon, Meta, Microsoft), networking & 5G, consumer electronics, automotive, and more.

### 1.3 Growth Drivers

Key growth drivers discussed in the deck include:

- Structural increase in **CSP capex** for AI infrastructure, with AI-related investment becoming a larger share of total spending. :contentReference[oaicite:3]{index=3}  
- The push for **better energy efficiency and lower TCO** in AI inference workloads, where ASICs can offer 40–60% lower total cost compared with general-purpose GPUs for specific models. :contentReference[oaicite:4]{index=4}  
- The strategic desire of cloud providers to differentiate their AI services and reduce dependence on external GPU vendors.

### 1.4 ASIC vs GPU

The analysis highlights a clear division of labor:

- **GPUs**  
  - Highly programmable and versatile  
  - Strong at training complex, non-linear models  
  - Better suited for environments where model architectures evolve rapidly
- **ASICs**  
  - Customized for specific workloads  
  - Lower energy consumption and cost per unit of compute for stable, large-scale inference  
  - Particularly attractive when model weights are fixed and the main job is massive matrix multiplication. :contentReference[oaicite:5]{index=5}  

The conclusion is that ASICs are increasingly used as the **core architecture for AI inference**, while GPUs maintain an advantage on the training side.

### 1.5 Case Study – Broadcom (AVGO)

The deck uses Broadcom as a key case study:

- AI-related business has grown from less than 5% of semiconductor solution revenue in FY2019 to around 15% in FY2023. :contentReference[oaicite:6]{index=6}  
- Broadcom’s gross margin has reached ~67%, significantly higher than some competitors such as MediaTek (~49%), reflecting its strong position in high-barrier IP and advanced packaging. :contentReference[oaicite:7]{index=7}  
- The company benefits from strong demand for Google’s next-generation TPUs and ongoing CoWoS capacity expansion.

### 1.6 Risks & Monitoring Points

The slides also discuss:

- **Technology risk:** architectural shifts or new paradigms that could reduce the relative advantage of ASICs.
- **Customer concentration:** reliance on a small number of hyperscale CSP customers.
- **Supply chain constraints:** advanced packaging capacity (e.g., CoWoS) as a bottleneck.
- **Competition:** other design houses and CSP in-house chip projects.

### 1.7 Files

- `ai-asic/ai_asic_industry_overview_ellen_2025.pptx`  
- `ai-asic/ai_asic_industry_overview_ellen_2025.pdf`

---

## Future Additions

Over time, this repository will be extended with:

- Additional **industry notes** on AI servers, racks, power and cooling, and networking.
- Short **single-name equity memos** linked to my own tools (e.g., Fortune Ticker) and research workflow.
