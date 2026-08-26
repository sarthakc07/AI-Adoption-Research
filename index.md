# Industrial AI Adoption & Digital Transformation
**Bridging the gap between technical prototypes and sustainable enterprise systems.**

---

## 🎯 The Mission: AI & Organizational Change
While artificial intelligence offers immense potential for industrial optimization, its adoption frequently stalls. Organizations often treat AI deployment as a standard software upgrade rather than a systemic and cultural transformation. 

My research investigates the friction points in enterprise AI integration through a socio-technical lens. By synthesizing existing literature and processing real-world AI incident datasets, I focus on identifying and mitigating the barriers that emerge from the complex interactions between human workflows, technological constraints, and organizational structures.

---

## 📊 Literature Synthesis: The HTO Framework
To understand why AI implementations fail in enterprise settings, I conducted a comprehensive analysis of 15 core research papers, grounding the findings in the **Human-Technology-Organization (HTO)** model. 

Rather than viewing algorithms in a vacuum, this synthesis reveals that successful digital transformation requires joint optimization across three domains:

**1. The Human Bottleneck:** Trust deficits, cognitive resistance, and skill mismatches are primary drivers of friction, often outpacing purely technical failures.  

**2. Technological Constraints:** Algorithmic opacity, data silos, and legacy IT misalignment prevent seamless scaling of AI initiatives.  

**3. Organizational Governance:** A lack of rigid decision-making structures, unclear ROI, and policy uncertainty create environments where AI cannot be safely or effectively deployed.

This theoretical foundation was subsequently validated by engineering a Python-based ETL pipeline to parse and categorize over 16,000 real-world AI incidents into these HTO failure modes.

---

### Empirical Findings (N = 1,607)

| Socio-Technical Dimension | Incident Count | Percentage | Primary Indicators |
| :--- | :--- | :--- | :--- |
| **Human Oversight / Trust Breakdown** | 1,189 | 74.0% | Operator error, automation bias, user mistrust, lack of training |
| **System Reliability / Technical Deficit** | 707 | 44.0% | Model hallucinations, data leaks, system bugs, integration failures |
| **Governance / Organizational Deficit** | 436 | 27.1% | Compliance non-conformance, shadow AI, missing corporate policy |
| **Cross-Dimensional Overlap** | 698 | 43.4% | Incidents spanning 2 or more HTO dimensions simultaneously |

<br>

### Visualizing the Empirical Data

![HTO AI Incidents Distribution](https://raw.githubusercontent.com/sarthakc07/AI-sociotechnical-incidents-analysis/main/data/processed/hto_distribution_chart.png)

![OECD Longitudinal Trends](https://raw.githubusercontent.com/sarthakc07/AI-sociotechnical-incidents-analysis/main/data/processed/oecd_longitudinal_trends.png)

---

## 📚 Literature Repository (15 Core Papers)
Below is the foundational research synthesized for this project. 

### Human Dynamics & Trust
*   **Bérubé, M. & Vial, G. (2021).** *Barriers to the Implementation of AI in Organizations: Findings from a Delphi Study. Proceedings of the 54th Hawaii International Conference on System Sciences, 6702-6711.* Journal Name. [Read Paper](https://scholarspace.manoa.hawaii.edu/server/api/core/bitstreams/8cbde544-0c2c-4781-9e78-72bbab3904a1/content)
*   **Bettoni, A. & Matteri, D. (2021).** *An AI adoption model for SMEs: a conceptual framework. IFAC PapersOnLine, 54(1), 702-708.* Journal Name. [Read Paper](https://www.sciencedirect.com/science/article/pii/S2405896321008259)
*   **Dondorf, V & Dumitrescu, R. (2025).** *Evaluation Of The Challenges In Implementing AI Across The Different Phases - Empirical Insights Derived From AI Implementation Projects In Industry. CPSL 2025, 207-220.* Journal Name. [Read Paper](https://repo.uni-hannover.de/items/d0a23da2-6126-422f-bce3-0e7d6bc897f8)
*   **Riedl, M. O. (2019).** *Human-centered artificial intelligence and machine learning. Human Behavior and Emerging Technologies, 1, 33-36.* Journal Name. [Read Paper](https://onlinelibrary.wiley.com/doi/full/10.1002/hbe2.117)
*   **Grünbichler, R. (2023).** *Implementation Barriers of Artificial Intelligence in Companies. Graz University of Technology, 193-203.* Journal Name. [Read Paper](https://www.researchgate.net/profile/Gruenbichler-Rudolf/publication/371958928_IMPLEMENTATION_BARRIERS_OF_ARTIFICIAL_INTELLIGENCE_IN_COMPANIES/links/649ed4abb9ed6874a5eb4517/IMPLEMENTATION-BARRIERS-OF-ARTIFICIAL-INTELLIGENCE-IN-COMPANIES.pdf)

### Technological & Systemic Friction
*   **Kramarenko, A. (2025).** *Artificial Intelligence for Small and Medium Business: Perspectives and Challenges. Journal of Engineering Management and Competitiveness, 15(1), 43-56.* Journal Name. [Read Paper](https://d1wqtxts1xzle7.cloudfront.net/123312253/ARTIFICIAL_INTELLIGENCE_FOR_SMALL_AND_MEDIUM_BUSINESS-libre.pdf?1750085781=&response-content-disposition=inline%3B+filename%3DARTIFICIAL_INTELLIGENCE_FOR_SMALL_AND_ME.pdf&Expires=1786978536&Signature=EdI0Uj0hIhKBhcYpAXFijuzrVvOGhOgAR3K8yjyxClJ~QFygworEim-tDWZ3chG0mZst4iq6fdG~YRY6M0VaiziGD4jIKqPHoIoZCAO9Q2hF6uBfsKeRPYtGvozWOpVYl7VMFYb~ZA8x6NrghLrZgTCf3qwZ6E6rQCtYPq3OExAVgx9t0pdMYYZ4pe1Hog~a66Imv4ibZJhmlNZl12u8U4bmiXNspPN~NlQjvGHEy9ofKWSspkIj9jVJ3gQSFnChyXLitSdZc54sAB8hWKx2QPLih6hYeFIo4TavApGrljaffXFguTbcCIQVOb7zxtS2uILh315F4t-hTiXVxiJlhA__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA)
*   **Ulrich, P. & Frank, V. (2021).** *Adoption of artificial intelligence technologies in German SMEs — Results from an empirical study. Virtus, 76-84.* Journal Name. [Read Paper](https://aisel.aisnet.org/pacis2021/189/)
*   **Hamm, P. & Klesel, M. (2021).** *Success Factors for the Adoption of Artificial Intelligence in Organizations: A Literature Review. AMCIS 2021 Proceedings, 1-10.* Journal Name. [Read Paper](https://research.utwente.nl/en/publications/success-factors-for-the-adoption-of-artificial-intelligence-in-or/)
*   **Irman, D., & Putra, D. (2025).** *AI Adoption in Business: Opportunities and Challenges for Start-ups. International Journal of Business, Economics and Social Development, 6(1), 99-104.* Journal Name. [Read Paper](https://www.researchgate.net/publication/389871609_AI_Adoption_in_Business_Opportunities_and_Challenges_for_Start-ups)
*   **Zavodna, L. S. (2024).** *Barriers to the implementation of artificial intelligence in small and medium-sized enterprises: Pilot study* Journal Name. [Read Paper](https://reference-global.com/article/10.22367/jem.2024.46.13)

### Organizational Governance & Strategy
*   **Schönberger, M. (2023).** *Artificial Intelligence for Small and Medium-Sized Enterprises: Identifying Key Applications and Challenges. Journal of Business Management, 21, 89-112.* Journal Name. [Read Paper](https://journals.riseba.eu/index.php/jbm/article/view/336)
*   **Zavodna, L. S., Überwimmer, M., & Frankus, E. (2024).** *Barriers to the implementation of artificial intelligence in small and medium-sized enterprises: Pilot study. Journal of Economics and Management, 46, 331-352.* Journal Name. [Read Paper](https://reference-global.com/article/10.22367/jem.2024.46.13)
*   **Bérubé, M. & Vial, G. (2021).** *Barriers to the Implementation of AI in Organizations: Findings from a Delphi Study. Proceedings of the 54th Hawaii International Conference on System Sciences, 6702-6711.* Journal Name. [Read Paper](https://scholarspace.manoa.hawaii.edu/server/api/core/bitstreams/8cbde544-0c2c-4781-9e78-72bbab3904a1/content)
*   **Kramarenko, A. (2025).** *Artificial Intelligence for Small and Medium Business: Perspectives and Challenges. Journal of Engineering Management and Competitiveness, 15(1), 43-56.* Journal Name. [Read Paper](https://d1wqtxts1xzle7.cloudfront.net/123312253/ARTIFICIAL_INTELLIGENCE_FOR_SMALL_AND_MEDIUM_BUSINESS-libre.pdf?1750085781=&response-content-disposition=inline%3B+filename%3DARTIFICIAL_INTELLIGENCE_FOR_SMALL_AND_ME.pdf&Expires=1786978536&Signature=EdI0Uj0hIhKBhcYpAXFijuzrVvOGhOgAR3K8yjyxClJ~QFygworEim-tDWZ3chG0mZst4iq6fdG~YRY6M0VaiziGD4jIKqPHoIoZCAO9Q2hF6uBfsKeRPYtGvozWOpVYl7VMFYb~ZA8x6NrghLrZgTCf3qwZ6E6rQCtYPq3OExAVgx9t0pdMYYZ4pe1Hog~a66Imv4ibZJhmlNZl12u8U4bmiXNspPN~NlQjvGHEy9ofKWSspkIj9jVJ3gQSFnChyXLitSdZc54sAB8hWKx2QPLih6hYeFIo4TavApGrljaffXFguTbcCIQVOb7zxtS2uILh315F4t-hTiXVxiJlhA__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA)
*   **Gumbo, L., & Booyse, N. J. (2025).** *Artificial Intelligence Implementation Strategies in Business: A Systematic Review. Business Excellence and Management, 15(5), 92-110.* Journal Name. [Read Paper](https://beman.ase.ro/special_issue_5/9.pdf)

---
*Developed as part of independent research on industrial AI transformation.*
