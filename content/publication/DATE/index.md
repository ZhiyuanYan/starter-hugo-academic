---
title: "AsymSAT: Accelerating SAT Solving with Asymmetric Graph-based Model Prediction"
authors:
- admin
- Min Li
- Zhengyuan Shi
- Wenjie Zhang
- Ying-Cong Chen
- Zhiyi Yuan
- Hongce Zhang
author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-06-02T00:00:00Z"
# doi: "10.1021/acsami.1c22466"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-11-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Design, Automation and Test in Europe"
publication_short: "DATE"

abstract: The Boolean satisfiability problem (SAT) is the foundational problem in electronic design automation (EDA). Recent efforts have explored the use of graph neural networks (GNNs) in SAT solving.However, for a subset of symmetric SAT problems, we unveil that the current GNN-based end-to-end SAT solvers are bound to yield incorrect outcomes as they are unable to break symmetry in variable assignments, while symmetric structure is prevalent in logic circuits such as miter circuits for equivalence checking and cryptographic circuits with XOR gates. In response, we introduce AsymSAT, an innovative GNN architecture coupled with recurrent neural networks (RNNs) to produce asymmetric models. Moreover, we bring up a method to integrate machine-learning-based SAT assignment prediction with classic SAT solvers and demonstrate its advantage on non-trivial SAT instances including logic equivalence checking and cryptographic analysis with an average of 75.45% speed-up.

# Summary. An optional shortened abstract.
summary: Boolean satisfiability problem, machine learning

# tags:
# - Source Themes
featured: false
---
