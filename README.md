# Equity Research & Industry Notes

A curated collection of my undergraduate equity research and industry overview work, with a focus on AI infrastructure and semiconductor-related themes.

---

## 1. AI ASIC Industry Overview

**Language:** Chinese  
**Format:** Slide deck (PPTX / PDF)  
**Role:** Team member (research, structuring, and writing)  
**Topic:** AI ASIC supply chain, growth drivers, risks, and investment ideas  

### 1.1 Scope & Objectives

This piece provides a structured overview of the AI ASIC industry and its role within the broader AI infrastructure stack. It aims to:

- Map out the **value chain** from IP & EDA, IC design, foundry, advanced packaging, to downstream applications (data centers, networking, consumer, automotive).  
- Compare **ASIC vs GPU** in terms of performance, cost, flexibility, and typical use cases.  
- Analyze how hyperscale cloud providers (CSPs) are driving ASIC adoption through self-developed accelerators.  
- Identify potential **investment candidates** and key factors to monitor going forward.  

### 1.2 Industry Value Chain

The deck summarizes the AI ASIC supply chain as:

- **IP & EDA:** ARM, Synopsys, Cadence – providing fundamental IP blocks and design tools.  
- **IC Design & Design Services:**  
  - Taiwan-based players such as Alchip (世芯-KY), Global Unichip (創意), Faraday (智原)  
  - Global players such as Broadcom (AVGO), Marvell (MRVL), MediaTek, etc.  
- **Foundry:**  
  - Pure-play: TSMC, UMC, GlobalFoundries, SMIC  
  - IDM + Foundry: Intel, Samsung  
- **Packaging & Testing:** ASE, PTI, Amkor, KYEC, plus TSMC’s CoWoS and other advanced packaging lines.  
- **Downstream Applications:** Hyperscale data centers (Google, Amazon, Meta, Microsoft), networking & 5G, consumer electronics, automotive, etc.  

### 1.3 Key Drivers & Industry Logic

Key growth drivers discussed in the deck include:

- Structural increase in **CSP capex** for AI infrastructure, with AI-related investment becoming a larger share of total spending.  
- The push for **better energy efficiency and lower TCO** in AI inference workloads, where ASICs can offer significantly lower cost compared with general-purpose GPUs for specific models.  
- The strategic desire of cloud providers to differentiate their AI services and reduce dependence on external GPU vendors.  

The analysis highlights a division of labor:

- **GPUs** remain strong for training and for environments where models and architectures change quickly.  
- **ASICs** are attractive for large-scale, stable inference workloads where model weights are fixed and cost / energy efficiency dominate.  

### 1.4 Case Study – Broadcom (AVGO)

The slide deck uses Broadcom as a case study to connect industry structure to a specific name:

- AI-related business has grown to a meaningful share of semiconductor solution revenue.  
- Gross margin is structurally higher than some competitors, reflecting strong IP and packaging advantages.  
- The company benefits from demand for custom accelerators (e.g., Google TPUs) and expanding advanced packaging capacity.  

### 1.5 Risks & Monitoring Points

The deck also discusses:

- **Technology risk:** new architectures that may change the balance between GPUs and ASICs.  
- **Customer concentration:** reliance on a small number of hyperscale CSP customers.  
- **Supply chain bottlenecks:** advanced packaging (e.g., CoWoS) as a limiting factor.  
- **Competition:** other design houses and CSP in-house chip projects.  

### 1.6 Files

- `ai-asic/ai_asic_industry_overview_ellen_2025.pptx`  
- `ai-asic/ai_asic_industry_overview_ellen_2025.pdf`  

---

## 2. Single-Name Equity Research – Alchip (3661.TW)

**Language:** Chinese  
**Format:** Slide deck (PPTX / PDF)  
**Role:** Team member (research, structuring, and writing)  
**Company / Ticker:** Alchip Technologies (世芯-KY) / 3661.TW  
**Topic:** Business model (design service / turnkey), AI ASIC project pipeline, growth catalysts, risk factors, and valuation conclusion  

### 2.1 Scope & Objectives

This deck is a single-name equity research note that builds on the industry framework and answers three core questions:

- **Positioning:** Where does Alchip sit in the AI ASIC value chain, and what is its role in customer programs?  
- **Earnings power:** What are the growth engines (major programs, nodes, ramps), and how do they translate into revenue / margin expansion?  
- **Risk & validation:** What could go wrong (customer concentration, geopolitics, execution), and what datapoints validate or falsify the thesis?  

### 2.2 Company Positioning (Design Service / Turnkey)

The research frames Alchip as a Taiwan-based design service / ASIC turnkey provider, typically involved in:

- Back-end and implementation work (e.g., physical design), tape-out support, and mass production delivery  
- Coordination across foundry + advanced packaging ecosystems for high-performance AI accelerators  
- Leveraging deep experience in advanced nodes and packaging requirements (2.5D/3D integration, high bandwidth interfaces)  

### 2.3 Key Growth Engines & Catalysts

Key catalysts emphasized in the deck include:

- **AWS Trainium program ramp:** The note highlights a major AWS AI accelerator program (Trainium generation) as a central driver of forward growth, with a visible ramp schedule and meaningful revenue contribution once mass production begins.  
- **Next-node pipeline (2nm):** Follow-on generations are discussed as longer-duration optionality contingent on execution and schedule.  
- **Automotive ADAS ASIC:** A non-cloud growth leg is included via automotive ASIC programs, positioned as diversification beyond hyperscaler demand cycles.  
- **Ecosystem shifts:** Industry trends that lower integration barriers (e.g., opening up interconnect / platform compatibility) are framed as potential tailwinds for custom ASIC penetration.  

### 2.4 Key Risks & Monitoring Points

The deck flags several risks that are especially important for AI ASIC design service names:

- **Customer concentration risk:** Revenue can be heavily skewed toward one hyperscaler program at peak ramp.  
- **Execution and schedule risk:** Delays in tape-out, yield learning, packaging capacity, or customer deployment can shift the ramp curve materially.  
- **Geopolitical / export control risk:** Changes in regulatory constraints may affect customer ability to deploy or source advanced AI silicon.  
- **Supply chain constraints:** Advanced packaging and HBM availability remain critical bottlenecks for high-end AI accelerator volumes.  

Suggested monitoring indicators:

- Hyperscaler AI capex / deployment signals  
- Program milestone updates (tape-out, qualification, volume ramp)  
- Packaging capacity expansion (CoWoS / advanced packaging) and HBM supply dynamics  
- Management guidance and customer commentary on custom silicon strategy  

### 2.5 Files

- `ai-asic/ai_asic_industry_3661_ellen_2025.pptx`  
- `ai-asic/ai_asic_industry_3661_ellen_2025.pdf`  

---

## Future Additions

Over time, this repository may include:

- Additional **industry notes** on AI servers, racks, power and cooling, and networking.  
- More **single-name equity research memos** (design services, foundry, advanced packaging, HBM-related names).  
- Lightweight **data tables / charts** used in the research process (capex trackers, packaging capacity, key KPI dashboards).  
- Short write-ups linked to my own research workflow tools (e.g., Fortune Ticker).
