---
title: "AssertLLM: Generating Hardware Verification Assertions from Design Specifications via Multi-LLMs"
authors:
- admin #
- Wenji Fang #
- Mengming Li 
- Min Li
- Shang Liu
- Zhiyao Xie 
- Hongce Zhang
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2025-01-20T00:00:00Z"
# doi: "10.1021/acsami.1c22466"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Asia and South Pacific Design Automation Conference"
publication_short: "ASP-DAC"

abstract: Assertion-based verification (ABV) is a critical method to ensure logic designs comply with their architectural specifications. ABV requires assertions, which are generally converted from specifications through human interpretation by verification engineers. Existing methods for generating assertions from specification documents are limited to sentences extracted by engineers, discouraging their practical applications. In this work, we present AssertLLM, an automatic assertion generation framework that processes complete specification documents. AssertLLM can generate assertions from both natural language and waveform diagrams in specification files. It first converts unstructured specification sentences and waveforms into structured descriptions using natural language templates. Then, a customized Large Language Model (LLM) generates the final assertions based on these descriptions. Our evaluation demonstrates that AssertLLM can generate more accurate and higher-quality assertions compared to GPT-4o and GPT-3.5.

# Summary. An optional shortened abstract.

# tags:
# - Source Themes
featured: false
---
