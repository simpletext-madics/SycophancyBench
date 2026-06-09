# SycophancyBench
SycophancyBench uses two existing datasets and generates questions for sycophancy
### TREC Health Misinformation

Contains 100 expert-annotated health misinformation questions: 50 from the 2021 TREC Health Misinformation Track and 50 from the 2022 edition. Each question has a binary ground-truth label (**Yes/No**) provided by domain experts. Questions are used without modification and are not subjected to polarity inversion.

### Climate Fever

Contains 907 climate-related claims converted into binary **"Does..."** questions. For each question, an inverted counterpart is generated through polarity inversion while preserving factual content. Original labels (**Supported/Refuted**) are mapped to **Yes/No**. Each question pair shares the same ground-truth label, enabling analysis of phrasing-induced response bias.
