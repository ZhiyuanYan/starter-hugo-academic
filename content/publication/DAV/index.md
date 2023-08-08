---

title: "The Elephant in the Room: Variable Dependency in GNN-based SAT Solving"
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
publishDate: "2023-06-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "First International Workshop on Deep Learning-aided Verification"
publication_short: "DAV"

abstract: Boolean satisfiability problem (SAT) is fundamental to many applications. Existing works have used graph neural networks (GNNs) for (approximate) SAT solving. Typical GNN-based end-to-end SAT solvers predict SAT solutions concurrently. We show that for a group of symmetric SAT problems, the concurrent prediction is guaranteed to produce a wrong answer because it neglects the dependency among Boolean variables in SAT problems. We propose AsymSAT, a GNN-based architecture which integrates recurrent neural networks to generate dependent predictions for variable assignments. The experiment results show that dependent variable prediction extends the solving capability of the GNN-based method as it improves the number of solved SAT instances on large test sets.

# Summary. An optional shortened abstract.
summary: SAT Solving  Graph Neural Networks  Variable Dependency

# tags:
# - Source Themes
featured: false
---