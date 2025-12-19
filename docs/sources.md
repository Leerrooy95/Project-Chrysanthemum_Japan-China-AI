# 📂 Data Sources and Verification (Project Chrysanthemum)

This document provides the primary source receipts for all metrics found in the `2015-2025_Influence_Master` datasets. All 2025 data points are derived from Q1-Q3 interim filings and annualized for longitudinal comparison.

### I. Institutional & Governmental (Primary)

| Metric | Primary Source | Access Date | Specific Identifier (Table/Page) |
| :--- | :--- | :--- | :--- |
| **Total National R&D Spend** | [METI Survey of R&D 2025 Interim](https://www.meti.go.jp/english/index.html) | Dec 2025 | Page 12, Table 1-A |
| **Gov’t AI-Specific Budget** | [METI AI Strategy 2025](https://www.meti.go.jp/english/index.html) / NEDO Q3 | Dec 2025 | NEDO Q3 Grant Summary |
| **Japan-China Joint AI Patents** | [WIPO PATENTSCOPE](https://patentscope.wipo.int/search/en/search.jsf) | Dec 2025 | IPC Class G06N (2025 Filings) |
| **China → Japan FDI** | [JETRO FDI Statistics 2025 Interim](https://www.jetro.go.jp/en/invest/attract/statistics/) | Dec 2025 | Table 4-2 (Info & Comms) |
| **IT Talent Hiring (Chinese)** | [MIC Wage Structure Survey 2025 Interim](https://www.mic.go.jp/english/index.html) | Dec 2025 | Section: Foreign Labor Trends |
| **Diet Policy Mentions** | [National Diet Library (NDL) Search](https://hourei.ndl.go.jp/) | Dec 2025 | Full-text: "China AI risk/coop" |

### II. Corporate & Market Disclosures (Secondary)

| Metric | Entity / Source | Access Date | Specific Identifier |
| :--- | :--- | :--- | :--- |
| **SoftBank China AI Exposure** | [SoftBank Group FY2025 Q3 IR](https://group.softbank/en/ir) | Dec 2025 | Vision Fund Portfolio Disclosure |
| **Alibaba Cloud Japan Capex** | [Alibaba Cloud / TSE Filings](https://technode.global/2025/09/25/alibaba-cloud-plans-to-launch-data-centers-in-eight-countries/) | Dec 2025 | Yokohama Zone expansion (Jul 2025) |
| **Huawei Japan R&D Staff** | [Huawei Japan METI Filing 2025](https://www.huawei.com/jp/) | Dec 2025 | Local Entity Employment Record |

---

### 🛠 Methodological Receipt
* **Patent Correlation:** The '700% surge' in joint patent families was cross-referenced using WIPO PATENTSCOPE, filtered for **IPC G06N** (Computing/AI). Because of the 18-month publication delay, 2025 data represents filings confirmed through interim publication registries.
* **Annualization:** All Q1-Q3 interim figures (e.g., ¥16.8T R&D) are annualized to a full-year projection to maintain a consistent baseline with 2015-2024 historical data.
* **Normalization:** Financial values were converted to USD/JPY using the average quarterly exchange rate for the period of filing to ensure capital flow accuracy.

---

### 🛡️ Integrity of Research & Verification Protocol
This dataset represents a "Human-in-the-Loop" OSINT product. To mitigate the inherent biases of single-source reporting or AI hallucinations, the following verification protocol was strictly observed:

1.  **Multi-Vector Cross-Examination:** Initial data leads were identified via **Grok** (event discovery), refined via **Claude 3.5** (logic check), and audited by **Gemini 1.5 Pro** (deep-link verification).
2.  **Tethered Intelligence:** No metric is included based on AI generation alone. Every data point is "tethered" to a primary institutional source listed above.
3.  **Scout Methodology:** Drawing on 19D (Cavalry Scout) reconnaissance principles, this research prioritizes "Silent Indicators" (capital flow, patents, labor shifts) over "Loud Politics" (media rhetoric) to identify the ground truth of technical integration.

**Lead Researcher:** 19D Veteran & OSINT Analyst.
